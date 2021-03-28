---
title: Start Virtual Machine
description: Instructions for starting virtual machine and mitigating some issues
date: 2021-02-14 05:00:00 -0700
# date_updated:  # Optional and formatted like 'date' above
time_to_live: 1800
layout: post

pictures:
  mint-count-down:
    url:
      base: assets/print-screen/virtual-box/start-virtual-machine/mint-count-down/
      filter: relative_url

    img:
      alt: Print screen image of Virtual Machine boot count down for Mint live CD
      src: mint-count-down.jpeg
      width: 640
      height: 480
      loading: lazy
      decoding: async

    sources:
      - srcset: mint-count-down.avif
      - srcset: mint-count-down.jpeg
      - srcset: mint-count-down.png
      - srcset: mint-count-down.webp

  grub-menu-select-compatibility-mode:
    url:
      base: assets/print-screen/virtual-box/start-virtual-machine/grub-menu-select-compatibility-mode/
      filter: relative_url

    img:
      alt: Print screen image of Virtual Machine Grub menu selection
      src: grub-menu-select-compatibility-mode.jpeg
      width: 1024
      height: 768
      loading: lazy
      decoding: async

    sources:
      - srcset: grub-menu-select-compatibility-mode.avif
      - srcset: grub-menu-select-compatibility-mode.jpeg
      - srcset: grub-menu-select-compatibility-mode.png
      - srcset: grub-menu-select-compatibility-mode.webp

  grub-menu-non-uefi-compatibility-mode:
    url:
      base: assets/print-screen/virtual-box/start-virtual-machine/grub-menu-non-uefi-compatibility-mode/
      filter: relative_url

    img:
      alt: Print screen image of Virtual Box application 
      src: grub-menu-non-uefi-compatibility-mode.jpeg
      width: 640
      height: 480
      loading: lazy
      decoding: async

    sources:
      - srcset: grub-menu-non-uefi-compatibility-mode.avif
      - srcset: grub-menu-non-uefi-compatibility-mode.jpeg
      - srcset: grub-menu-non-uefi-compatibility-mode.png
      - srcset: grub-menu-non-uefi-compatibility-mode.webp
---



> Instructions for starting virtual machine and mitigating some issues


---


- [Start Virtual Machine][heading__start_virtual_machine]

- [Mint Count Down][heading__mint_count_down]

- [Grub Menu Selection][heading__grub_menu_selection]


---



## Start Virtual Machine
[heading__start_virtual_machine]: #start-virtual-machine


With the new Virtual Machine selected press the downward pointing _arrow_ beside `Start` button


Select `Normal Start` option


______


## Mint Count Down
[heading__mint_count_down]: #mint-count-down "Virtual Machine boot count down for Mint live CD"


A new window _should_ show up, if a _count down_ appears press arrow up/down <kbd>#&x2b06;</kbd> <kbd>#&x2b07;</kbd> keys for the Grub menu


{% include modules/includes-picture/picture.html name='mint-count-down' %}


______


## Grub Menu Selection
[heading__grub_menu_selection]: #grub-menu-selection "Virtual Machine Grub menu selection"


Within the Grub menu select _compatibility mode_ and press <kbd>Enter</kbd>


{% include modules/includes-picture/picture.html name='grub-menu-select-compatibility-mode' %}


**Warning**, if _`EFI`_ mode was not enabled within Virtual Box _`Settings`_, _`System`_, _`Motherboard`_ configurations, then the following screen may instead be presented...


{% include modules/includes-picture/picture.html name='grub-menu-non-uefi-compatibility-mode' %}


**[Next Page][next__page]**


[next__page]: {{ 'virtual-box/configure-live-boot' | absolute_url }} "Steps to preform within live-boot Linux instance prior to installation"

