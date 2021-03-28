---
title: Drivers
description: Install proprietary drivers if necessary
date: 2021-02-15 01:00:00 -0700
# date_updated:  # Optional and formatted like 'date' above
time_to_live: 1800
layout: page

pictures:
  menu-driver-manager:
    url:
      base: assets/print-screen/first-boot/drivers/menu-driver-manager/
      filter: relative_url

    img:
      alt: Print screen image of Virtual Machine menu Driver Manager
      src: menu-driver-manager.jpeg
      width: 800
      height: 600
      loading: lazy
      decoding: async

    sources:
      - srcset: menu-driver-manager.avif
      - srcset: menu-driver-manager.jpeg
      - srcset: menu-driver-manager.png
      - srcset: menu-driver-manager.webp
---



Click on `Menu` button then type `Driver Manager`


{% include modules/includes-picture/picture.html name='menu-driver-manager' %}


If host has a NVidia graphics card then it is a _good idea_ to enable the latest proprietary drivers to avoid system hanging during Shut Down or Reboot


[Next Page][next__page]


[next__page]: {{ 'first-boot/update-initramfs' | absolute_url }} "Update initial RAM file system"

