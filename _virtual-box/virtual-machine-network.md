---
title: Virtual Machine Network
description: Configuring network options for Virtual Machine within Virtual Box
date: 2021-02-14 03:00:00 -0700
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

  settings-network-not-attached:
    url:
      base: assets/print-screen/virtual-box/virtual-machine-network/settings-network-not-attached/
      filter: relative_url

    img:
      alt: Print screen image of Virtual Box application Settings for Network
      src: settings-network-not-attached.jpeg
      width: 758
      height: 478
      loading: lazy
      decoding: async

    sources:
      - srcset: settings-network-not-attached.avif
      - srcset: settings-network-not-attached.jpeg
      - srcset: settings-network-not-attached.png
      - srcset: settings-network-not-attached.webp
---



> Configuring network options for Virtual Machine within Virtual Box


---


- [Select Virtual Machine][heading__select_virtual_machine]

- [Settings Network Adapter][heading__settings_network_adapter]


---



## Select Virtual Machine
[heading__select_virtual_machine]: #select-virtual-machine


With the new Virtual Machine selected press the `Settings` button, or use <kbd>Crtl</kbd> <kbd>S</kbd> keyboard short-cut


{% include modules/includes-picture/picture.html name='select-virtual-machine' %}


______


## Settings Network Adapter
[heading__settings_network_adapter]: #settings-network-adapter


Under `Network` select `Attached to:` drop down and click `Not attached` option


{% include modules/includes-picture/picture.html name='settings-network-not-attached' %}


> Note, seems disabling the network is only required for EUFI installation to USB to avoid freezing of installer


**[Next Page][next__page]**


[next__page]: {{ 'virtual-box/find-target-usb' | absolute_url }} "Steps to target the correct USB device within Virtual Box"

