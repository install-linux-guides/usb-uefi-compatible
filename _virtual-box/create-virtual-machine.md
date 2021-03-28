---
title: Create Virtual Machine
description: Steps for making a new Virtual Machine within Virtual Box
date: 2021-02-14 00:00:00 -0700
# date_updated:  # Optional and formatted like 'date' above
time_to_live: 1800
layout: post

# attribution:
#   links:
#     - text:
#       href:
#       title:

pictures:
  open-virtual-box:
    url:
      base: assets/print-screen/virtual-box/create-virtual-machine/open-virtual-box/
      filter: relative_url

    img:
      alt: Print screen image of Virtual Box application without any virtual machines configured
      src: open-virtual-box.jpeg
      width: 960
      height: 571
      loading: lazy
      decoding: async

    sources:
      - srcset: open-virtual-box.avif
      - srcset: open-virtual-box.jpeg
      - srcset: open-virtual-box.png
      - srcset: open-virtual-box.webp

  create-virtual-machine:
    url:
      base: assets/print-screen/virtual-box/create-virtual-machine/create-virtual-machine/
      filter: relative_url

    img:
      alt: Print screen image of Virtual Box application Create Virtual Machine pop-up
      src: create-virtual-machine.jpeg
      width: 515
      height: 418
      loading: lazy
      decoding: async

    sources:
      - srcset: create-virtual-machine.avif
      - srcset: create-virtual-machine.jpeg
      - srcset: create-virtual-machine.png
      - srcset: create-virtual-machine.webp

  memory-size:
    url:
      base: assets/print-screen/virtual-box/create-virtual-machine/memory-size/
      filter: relative_url

    img:
      alt: Print screen image of Virtual Box application Memory size pop-up
      src: memory-size.jpeg
      width: 515
      height: 418
      loading: lazy
      decoding: async

    sources:
      - srcset: memory-size.avif
      - srcset: memory-size.jpeg
      - srcset: memory-size.png
      - srcset: memory-size.webp

  hard-disk:
    url:
      base: assets/print-screen/virtual-box/create-virtual-machine/hard-disk/
      filter: relative_url

    img:
      alt: Print screen image of Virtual Box application Hard disk pop-up
      src: hard-disk.jpeg
      width: 515
      height: 418
      loading: lazy
      decoding: async

    sources:
      - srcset: hard-disk.avif
      - srcset: hard-disk.jpeg
      - srcset: hard-disk.png
      - srcset: hard-disk.webp

  create-warning:
    url:
      base: assets/print-screen/virtual-box/create-virtual-machine/create-warning/
      filter: relative_url

    img:
      alt: Print screen image of Virtual Box application Create warning pop-up
      src: create-warning.jpeg
      width: 301
      height: 229
      loading: lazy
      decoding: async

    sources:
      - srcset: create-warning.avif
      - srcset: create-warning.jpeg
      - srcset: create-warning.png
      - srcset: create-warning.webp
---



> Steps for making a new Virtual Machine within Virtual Box


---


- [Open VirtualBox][heading__open_virtualbox]

- [Create Virtual Machine][heading__create_virtual_machine]

- [Configure Memory Size][heading__configure_memory_size]

- [Configure Hard Disk][heading__configure_hard_disk]

- [Confirm Create Warning][heading__confirm_create_warning]


---


## Open VirtualBox
[heading__open_virtualbox]: #open-virtualbox


First open of VirtualBox _should_ be similar to...


{% include modules/includes-picture/picture.html name='open-virtual-box' %}


______


## Create Virtual Machine
[heading__create_virtual_machine]: #create-virtual-machine


Click `New` button...


Within `Name` text field input a unique and descriptive string, eg. _`Live_Mint`_


Under `Type` drop-down select `Linux`


Under `Version` drop-down select the distribution, and be certain that selection matches the architecture of downloaded ISO eg. _`Other Linux (64-bit)`_


{% include modules/includes-picture/picture.html name='create-virtual-machine' %}


______


## Configure Memory Size
[heading__configure_memory_size]: #configure-memory-size


Click `Next` button...


Under `Memory size` select `2048`MB or greater


{% include modules/includes-picture/picture.html name='memory-size' %}


______


## Configure Hard Disk
[heading__configure_hard_disk]: #configure-hard-disk


Click `Next` button...


Under `Hard disk` select `Do not add a virtual hard disk`


{% include modules/includes-picture/picture.html name='hard-disk' %}


______


## Confirm Create Warning
[heading__confirm_create_warning]: #confirm-create-warning


Press `Create` button, then `Continue` button...


{% include modules/includes-picture/picture.html name='create-warning' %}


**[Next Page][next__page]**


[next__page]: {{ 'virtual-box/virtual-machine-storage' | absolute_url }} "Setting up storage for Virtual Machine within Virtual Box"

