---
title: Upgrade
description: Upgrade install Linux packages
date: 2021-02-15 00:00:00 -0700
# date_updated:  # Optional and formatted like 'date' above
time_to_live: 1800
layout: page

# attribution:
#   links:
#     - text:
#       href:
#       title:
---



Open a terminal emulator via keyboard shortcut <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>T</kbd>, or by clicking `Menu` button and typing `Terminal`, then issue the following commands...


```Bash
mkdir -p Documents/logs/sudo_apt-get_upgrade

sudo apt-get update

_log_path="${HOME}/Documents/logs/sudo_apt-get_upgrade/$(date +'%Y%m%d').script"

script -ac 'sudo apt-get upgrade' "${_log_path}"
```


Allow upgrade to complete!


[Next Page][next__page]


[next__page]: {{ 'first-boot/drivers' | absolute_url }} "Install proprietary drivers if necessary"

