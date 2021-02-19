---
title: Find Target USB
description: Steps to target the correct USB device within Virtual Box
date: 2021-02-14 04:00:00 -0700
# date_updated:  # Optional and formatted like 'date' above
time_to_live: 1800
layout: post
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


<picture>
  <source type="image/avif"
          scrset="{{ 'assets/print-screen/virtual-box/shared/select-virtual-machine/select-virtual-machine.avif' | absolute_url }}" />
  <source type="image/jpeg"
          scrset="{{ 'assets/print-screen/virtual-box/shared/select-virtual-machine/select-virtual-machine.jpeg' | absolute_url }}" />
  <source type="image/png"
          scrset="{{ 'assets/print-screen/virtual-box/shared/select-virtual-machine/select-virtual-machine.png' | absolute_url }}" />
  <source type="image/webp"
          scrset="{{ 'assets/print-screen/virtual-box/shared/select-virtual-machine/select-virtual-machine.webp' | absolute_url }}" />
  <img alt="Print screen image of Virtual Box application with one virtual machines configured"
       loading="lazy"
       decoding="async"
       width="960"
       height="571"
       src="{{ 'assets/print-screen/virtual-box/shared/select-virtual-machine/select-virtual-machine.jpeg' | absolute_url }}" />
</picture>


______


## Settings USB Controller
[heading__settings_usb_controller]: #settings-usb-controller


Select `USB` _tab_


Check the `Enable USB Controller` check-box such that it is checked


Select the version of USB that'll be used, `1.1`, `2.0`, or `3.0`


<picture>
  <source type="image/avif"
          scrset="{{ 'assets/print-screen/virtual-box/find-target-usb/settings-usb-controller/settings-usb-controller.avif' | absolute_url }}" />
  <source type="image/jpeg"
          scrset="{{ 'assets/print-screen/virtual-box/find-target-usb/settings-usb-controller/settings-usb-controller.jpeg' | absolute_url }}" />
  <source type="image/png"
          scrset="{{ 'assets/print-screen/virtual-box/find-target-usb/settings-usb-controller/settings-usb-controller.png' | absolute_url }}" />
  <source type="image/webp"
          scrset="{{ 'assets/print-screen/virtual-box/find-target-usb/settings-usb-controller/settings-usb-controller.webp' | absolute_url }}" />
  <img alt="Print screen image of Virtual Box application Settings USB controller"
       loading="lazy"
       decoding="async"
       width="758"
       height="478"
       src="{{ 'assets/print-screen/virtual-box/find-target-usb/settings-usb-controller/settings-usb-controller.jpeg' | absolute_url }}" />
</picture>


______


## Settings USB Filter Details
[heading__settings_usb_filter_details]: #settings-usb-filter-details


Beside the `USB Device Filters` select the second USB icon, the one with description similar to _"Adds new USB filter with all fields set to values of the selected USB..."_


> Note, which devices are currently available but do **not** select anything just yet


Unmount/eject the target USB drive from the host and note which device is no longer available within the previous drop-down


Plug in the target USB drive and select it from the previous drop-down menu


> Note, **VirtualBox will automatically unmount selected USB device(s)**! So be certain that the correct target is selected, especially if following along from another USB installed Operating System


Beside the `USB Device Filters` select the third USB icon, the one with description similar to _"Edits selected USB filter"_, and double check that the target USB device is described correctly


<picture>
  <source type="image/avif"
          scrset="{{ 'assets/print-screen/virtual-box/find-target-usb/settings-usb-filter-details/settings-usb-filter-details.avif' | absolute_url }}" />
  <source type="image/jpeg"
          scrset="{{ 'assets/print-screen/virtual-box/find-target-usb/settings-usb-filter-details/settings-usb-filter-details.jpeg' | absolute_url }}" />
  <source type="image/png"
          scrset="{{ 'assets/print-screen/virtual-box/find-target-usb/settings-usb-filter-details/settings-usb-filter-details.png' | absolute_url }}" />
  <source type="image/webp"
          scrset="{{ 'assets/print-screen/virtual-box/find-target-usb/settings-usb-filter-details/settings-usb-filter-details.webp' | absolute_url }}" />
  <img alt="Print screen image of Virtual Box application Settings USB filter"
       loading="lazy"
       decoding="async"
       width="350"
       height="403"
       src="{{ 'assets/print-screen/virtual-box/find-target-usb/settings-usb-filter-details/settings-usb-filter-details.jpeg' | absolute_url }}" />
</picture>


Click the `OK` button to confirm current changes to `USB Device Filters` and `Settings`, or use <kbd>Alt</kbd> <kbd>O</kbd> keyboard short-cut

