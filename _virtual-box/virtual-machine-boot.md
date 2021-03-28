---
title: Virtual Machine Boot
description: Configuring boot options for Virtual Machine within Virtual Box
date: 2021-02-14 02:00:00 -0700
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

  settings-system-motherboard:
    url:
      base: assets/print-screen/virtual-box/virtual-machine-boot/settings-system-motherboard/
      filter: relative_url

    img:
      alt: Print screen image of Virtual Box application without any virtual machines configured
      src: settings-system-motherboard.jpeg
      width: 758
      height: 478
      loading: lazy
      decoding: async

    sources:
      - srcset: settings-system-motherboard.avif
      - srcset: settings-system-motherboard.jpeg
      - srcset: settings-system-motherboard.png
      - srcset: settings-system-motherboard.webp

  settings-system-processor:
    url:
      base: assets/print-screen/virtual-box/virtual-machine-boot/settings-system-processor/
      filter: relative_url

    img:
      alt: Print screen image of Virtual Box application Settings for System Processor
      src: settings-system-processor.jpeg
      width: 758
      height: 478
      loading: lazy
      decoding: async

    sources:
      - srcset: settings-system-processor.avif
      - srcset: settings-system-processor.jpeg
      - srcset: settings-system-processor.png
      - srcset: settings-system-processor.webp
---



> Configuring boot options for Virtual Machine within Virtual Box


---


- [Select Virtual Machine][heading__select_virtual_machine]

- [Settings System Motherboard][heading__settings_system_motherboard]

- [Settings System Processor][heading__settings_system_processor]


---



## Select Virtual Machine
[heading__select_virtual_machine]: #select-virtual-machine


With the new Virtual Machine selected press the `Settings` button, or use <kbd>Crtl S</kbd> keyboard short-cut


{% include modules/includes-picture/picture.html name='select-virtual-machine' %}


______


## Settings System Motherboard
[heading__settings_system_motherboard]: #settings-system-motherboard


Under `System` check the `Enable EFI (special OSes only)` check-box


{% include modules/includes-picture/picture.html name='settings-system-motherboard' %}


______


## Settings System Processor
[heading__settings_system_processor]: #settings-system-processor


While within the `Settings` `System` screen, it may be a good idea to click the `Processor` tab and increase the number of `Processor(s)` too


{% include modules/includes-picture/picture.html name='settings-system-processor' %}


**[Next Page][next__page]**


[next__page]: {{ 'virtual-box/virtual-machine-network' | absolute_url }} "Configuring network options for Virtual Machine within Virtual Box"

