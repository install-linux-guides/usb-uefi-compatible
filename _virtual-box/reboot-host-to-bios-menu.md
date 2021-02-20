---
title: Reboot Host to BIOS Menu
description: Steps for rebooting host OS to BIOS menu
date: 2021-02-14 08:00:00 -0700
# date_updated:  # Optional and formatted like 'date' above
time_to_live: 1800
layout: post
---



If running a Linux based distribution run the following command within a terminal


```Bash
sudo systemctl reboot --firmware-setup
```


---


If running Windows 10 press and hold <kbd>shift</kbd> while clicking on Reset


Within `Choose an option` menu select `Troubleshoot`


Within `Troubleshoot` menu select `Advanced options`


Within `Advanced options` menu select `UEFI Firmware Settings`


Within `UEFI Firmware Settings` menu select `OK`


**[Next Page][next__page]**


[next__page]: {{ 'virtual-box/eufi-bootloader' | absolute_url }} "Configuring bootloader for booting from USB Grub2 before built-in drive of host"

