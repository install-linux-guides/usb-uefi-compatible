---
title: Virtual Machine Storage
description: Setting up storage for Virtual Machine within Virtual Box
date: 2021-02-14 01:00:00 -0700
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

  settings-storage-setup:
    url:
      base: assets/print-screen/virtual-box/virtual-machine-storage/settings-storage-setup/
      filter: relative_url

    img:
      alt: 'Print screen image of Virtual Box Storage Settings titled: Live_Mint - Settings'
      src: settings-storage-setup.jpeg
      width: 758
      height: 478
      loading: lazy
      decoding: async

    sources:
      - srcset: settings-storage-setup.avif
      - srcset: settings-storage-setup.jpeg
      - srcset: settings-storage-setup.png
      - srcset: settings-storage-setup.webp

  choose-virtual-optical-disk-file:
    url:
      base: assets/print-screen/virtual-box/virtual-machine-storage/choose-virtual-optical-disk-file/
      filter: relative_url

    img:
      alt: 'Print screen image of Virtual Box popup file browser titled: Please choose a virtual optical disk file'
      src: choose-virtual-optical-disk-file.jpeg
      width: 632
      height: 455
      loading: lazy
      decoding: async

    sources:
      - srcset: choose-virtual-optical-disk-file.avif
      - srcset: choose-virtual-optical-disk-file.jpeg
      - srcset: choose-virtual-optical-disk-file.png
      - srcset: choose-virtual-optical-disk-file.webp

  settings-storage-ok:
    url:
      base: assets/print-screen/virtual-box/virtual-machine-storage/settings-storage-ok/
      filter: relative_url

    img:
      alt: Print screen image of Virtual Box Storage Settings with virtual optical disk file configured
      src: settings-storage-ok.jpeg
      width: 758
      height: 478
      loading: lazy
      decoding: async

    sources:
      - srcset: settings-storage-ok.avif
      - srcset: settings-storage-ok.jpeg
      - srcset: settings-storage-ok.png
      - srcset: settings-storage-ok.webp
---



> Setting up storage for Virtual Machine within Virtual Box


---


- [Select Virtual Machine][heading__select_virtual_machine]

- [Settings Storage Setup][heading__settings_storage_setup]

- [Choose Virtual Optical Disk File][heading__choose_virtual_optical_disk_file]

- [Settings Storage OK][heading__settings_storage_ok]


---



## Select Virtual Machine
[heading__select_virtual_machine]: #select-virtual-machine


With the new Virtual Machine selected press the `Settings` button, or use <kbd>Crtl</kbd> <kbd>S</kbd> keyboard short-cut


{% include modules/includes-picture/picture.html name='select-virtual-machine' %}


______


## Settings Storage Setup
[heading__settings_storage_setup]: #settings-storage-setup


Select `Storage` _tab_


Under `Storage Devices` select the `Empty` virtual drive


Under `Attributes` check the `Live CD/DVD` checkbox such that it is checked


{% include modules/includes-picture/picture.html name='settings-storage-setup' %}


______


## Choose Virtual Optical Disk File
[heading__choose_virtual_optical_disk_file]: #choose-virtual-optical-disk-file


Click the _disk_ icon, select _`Choose Virtual Optical Disk File`_ option, and navigate to the downloaded Linux ISO file


{% include modules/includes-picture/picture.html name='choose-virtual-optical-disk-file' %}


______


## Settings Storage OK
[heading__settings_storage_ok]: #settings-storage-ok


Click the `OK` button to confirm current changes to Settings, or use <kbd>Alt</kbd> <kbd>O</kbd> keyboard short-cut


{% include modules/includes-picture/picture.html name='settings-storage-ok' %}


**[Next Page][next__page]**


[next__page]: {{ 'virtual-box/virtual-machine-boot' | absolute_url }} "Configuring boot options for Virtual Machine within Virtual Box"

