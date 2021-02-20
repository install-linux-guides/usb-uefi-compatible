---
title: Update `initramfs`
description: Update initial RAM file system
date: 2021-02-15 02:00:00 -0700
# date_updated:  # Optional and formatted like 'date' above
time_to_live: 1800
layout: page
---



Update _`initramfs`_ with the following commands...


```Bash
mkdir -p ${HOME}/Documents/logs/sudo_update-initramfs

_log_path="${HOME}/Documents/logs/sudo_update-initramfs/$(date +'%Y%m%d').script"

script -ac 'sudo update-initramfs -uv' "${_log_path}"
```


[Next Page][next__page]


[next__page]: {{ 'first-boot/configure-grub2' | absolute_url }} "Grub configurations that mitigate known dual-boot issues"

