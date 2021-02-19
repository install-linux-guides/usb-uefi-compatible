---
title: Virtual Machine Network
description: Configuring network options for Virtual Machine within Virtual Box
date: 2021-02-14 03:00:00 -0700
# date_updated:  # Optional and formatted like 'date' above
time_to_live: 1800
layout: post
---



> Configuring network options for Virtual Machine within Virtual Box


---


- [Select Virtual Machine][heading__select_virtual_machine]

- [Settings Network Adapter][heading__settings_network_adapter]


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


## Settings Network Adapter
[heading__settings_network_adapter]: #settings-network-adapter


Under `Network` select `Attached to:` drop down and click `Not attached` option


<picture>
  <source type="image/avif"
          scrset="{{ 'assets/print-screen/virtual-box/virtual-machine-network/settings-network-not-attached/settings-network-not-attached.avif' | absolute_url }}" />
  <source type="image/jpeg"
          scrset="{{ 'assets/print-screen/virtual-box/virtual-machine-network/settings-network-not-attached/settings-network-not-attached.jpeg' | absolute_url }}" />
  <source type="image/png"
          scrset="{{ 'assets/print-screen/virtual-box/virtual-machine-network/settings-network-not-attached/settings-network-not-attached.png' | absolute_url }}" />
  <source type="image/webp"
          scrset="{{ 'assets/print-screen/virtual-box/virtual-machine-network/settings-network-not-attached/settings-network-not-attached.webp' | absolute_url }}" />
  <img alt="Print screen image of Virtual Box application Settings for Network"
       loading="lazy"
       decoding="async"
       width="758"
       height="478"
       src="{{ 'assets/print-screen/virtual-box/virtual-machine-network/settings-network-not-attached/settings-network-not-attached.jpeg' | absolute_url }}" />
</picture>


> Note, seems disabling the network is only required for EUFI installation to USB to avoid freezing of installer

