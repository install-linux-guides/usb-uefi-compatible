---
title: Find Target USB
description: Steps to target the correct USB device within Virtual Box
date: 2021-02-14 04:00:00 -0700
# date_updated:  # Optional and formatted like 'date' above
time_to_live: 1800
layout: post

pictures:
  select-virtual-machine:
    url:
      base: assets/print-screen/virtual-box/shared/select-virtual-machine/
      filter: relative_url

    img:
      alt: Print screen image of Virtual Box application with one virtual machines configured
      src: select-virtual-machine.jpeg
      width: 960
      height: 571
      loading: lazy
      decoding: async

    sources:
      - srcset: select-virtual-machine.avif
      - srcset: select-virtual-machine.jpeg
      - srcset: select-virtual-machine.png
      - srcset: select-virtual-machine.webp

  settings-usb-controller:
    url:
      base: assets/print-screen/virtual-box/find-target-usb/settings-usb-controller/
      filter: relative_url

    img:
      alt: Print screen image of Virtual Box application Settings USB controller
      src: settings-usb-controller.jpeg
      width: 758
      height: 478
      loading: lazy
      decoding: async

    sources:
      - srcset: settings-usb-controller.avif
      - srcset: settings-usb-controller.jpeg
      - srcset: settings-usb-controller.png
      - srcset: settings-usb-controller.webp

  settings-usb-filter-details:
    url:
      base: assets/print-screen/virtual-box/find-target-usb/settings-usb-filter-details/
      filter: relative_url

    img:
      alt: Print screen image of Virtual Box application Settings USB filter
      src: settings-usb-filter-details.jpeg
      width: 350
      height: 403
      loading: lazy
      decoding: async

    sources:
      - srcset: settings-usb-filter-details.avif
      - srcset: settings-usb-filter-details.jpeg
      - srcset: settings-usb-filter-details.png
      - srcset: settings-usb-filter-details.webp
---



> Steps to target the correct USB device within Virtual Box


---


- [Select Virtual Machine][heading__select_virtual_machine]

- [Settings USB Controller][heading__settings_usb_controller]

- [Settings USB Filter Details][heading__settings_usb_controller]


---


## Select Virtual Machine
[heading__select_virtual_machine]: #select-virtual-machine


With the new Virtual Machine selected press the `Settings` button, or use <kbd>Crtl</kbd> <kbd>S</kbd> keyboard short-cut


{% include modules/includes-picture/picture.html name='select-virtual-machine' %}


______


## Settings USB Controller
[heading__settings_usb_controller]: #settings-usb-controller


Select `USB` _tab_


Check the `Enable USB Controller` check-box such that it is checked


Select the version of USB that'll be used, `1.1`, `2.0`, or `3.0`


{% include modules/includes-picture/picture.html name='settings-usb-controller' %}


______


## Settings USB Filter Details
[heading__settings_usb_filter_details]: #settings-usb-filter-details


Beside the `USB Device Filters` select the second USB icon, the one with description similar to _"Adds new USB filter with all fields set to values of the selected USB..."_


> Note, which devices are currently available but do **not** select anything just yet


Unmount/eject the target USB drive from the host and note which device is no longer available within the previous drop-down


Plug in the target USB drive and select it from the previous drop-down menu


> Note, **VirtualBox will automatically unmount selected USB device(s)**! So be certain that the correct target is selected, especially if following along from another USB installed Operating System


Beside the `USB Device Filters` select the third USB icon, the one with description similar to _"Edits selected USB filter"_, and double check that the target USB device is described correctly


{% include modules/includes-picture/picture.html name='settings-usb-controller' %}


Click the `OK` button to confirm current changes to `USB Device Filters` and `Settings`, or use <kbd>Alt</kbd> <kbd>O</kbd> keyboard short-cut


**[Next Page][next__page]**


[next__page]: {{ 'virtual-box/start-virtual-machine' | absolute_url }} "Instructions for starting virtual machine and mitigating some issues"

