---
title: Configure Grub2
description:
date: 2021-02-15 03:00:00 -0700
# date_updated:  # Optional and formatted like 'date' above
time_to_live: 1800
layout: post
---



Modify Grub configurations with the following...


> Note, one should do this _by hand_ (eg. with `vim` or `nano`), because there are some  configurations to add and some to modify.


**`/etc/default/grub` (snip)**


```
## Save the last used OS and auto-select it, because unattended
##   Windows updates may otherwise break the host system
GRUB_DEFAULT=saved
GRUB_SAVEDEFAULT=true

## Be explicit in countdown style and timeout
GRUB_TIMEOUT_STYLE=countdown
GRUB_TIMEOUT=15

## Wait indefinitely for root file-system to become available
GRUB_CMDLINE_LINUX_DEFAULT="rootwait"

## Check filesystem on each boot
##   Note, view logs with: journalctl -b --no-pager | grep 'systemd-fsck'
GRUB_CMDLINE_LINUX="fsck.mode=force"

##   Or use the following to attempt _safe_ fixes with fsck
# GRUB_CMDLINE_LINUX="fsck.repair=preen"
```


Update Grub with the following commands, which _should_ auto detect (and add) other Operating Systems to available boot options...


```Bash
mkdir -p ${HOME}/Documents/logs/sudo_update-grub

_log_path="${HOME}/Documents/logs/sudo_update-grub/$(date +'%Y%m%d').script"

script -ac 'sudo update-grub' "${_log_path}"
```

