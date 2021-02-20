---
title: Drivers
description: Install proprietary drivers if necessary
date: 2021-02-15 01:00:00 -0700
# date_updated:  # Optional and formatted like 'date' above
time_to_live: 1800
layout: page
---



Click on `Menu` button then type `Driver Manager`


<picture>
  <source type="image/avif"
          scrset="{{ 'assets/print-screen/first-boot/drivers/menu-driver-manager/menu-driver-manager.avif' | absolute_url }}" />
  <source type="image/jpeg"
          scrset="{{ 'assets/print-screen/first-boot/drivers/menu-driver-manager/menu-driver-manager.jpeg' | absolute_url }}" />
  <source type="image/png"
          scrset="{{ 'assets/print-screen/first-boot/drivers/menu-driver-manager/menu-driver-manager.png' | absolute_url }}" />
  <source type="image/webp"
          scrset="{{ 'assets/print-screen/first-boot/drivers/menu-driver-manager/menu-driver-manager.webp' | absolute_url }}" />
  <img alt="Print screen image of Virtual Machine menu Driver Manager"
       loading="lazy"
       decoding="async"
       width="800"
       height="600"
       src="{{ 'assets/print-screen/first-boot/drivers/menu-driver-manager/menu-driver-manager.jpeg' | absolute_url }}" />
</picture>


If host has a NVidia graphics card then it is a _good idea_ to enable the latest proprietary drivers to avoid system hanging during Shut Down or Reboot


[Next Page][next__page]


[next__page]: {{ 'first-boot/update-initramfs.html' | absolute_url }} "Update initial RAM file system"

