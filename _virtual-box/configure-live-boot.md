---
title: Configure Live Boot
description: Steps to preform within live-boot Linux instance prior to installation
date: 2021-02-14 06:00:00 -0700
# date_updated:  # Optional and formatted like 'date' above
time_to_live: 1800
layout: post

pictures:
  settings-screen-saver:
    url:
      base: assets/print-screen/virtual-box/configure-live-boot/settings-screen-saver/
      filter: relative_url

    img:
      alt: Print screen image of Virtual Machine Settings Screen Saver
      src: settings-screen-saver.jpeg
      width: 800
      height: 600
      loading: lazy
      decoding: async

    sources:
      - srcset: settings-screen-saver.avif
      - srcset: settings-screen-saver.jpeg
      - srcset: settings-screen-saver.png
      - srcset: settings-screen-saver.webp

  settings-lock-screen:
    url:
      base: assets/print-screen/virtual-box/configure-live-boot/settings-lock-screen/
      filter: relative_url

    img:
      alt: Print screen image of Virtual Machine Settings Lock Screen
      src: settings-lock-screen.jpeg
      width: 800
      height: 600
      loading: lazy
      decoding: async

    sources:
      - srcset: settings-lock-screen.avif
      - srcset: settings-lock-screen.jpeg
      - srcset: settings-lock-screen.png
      - srcset: settings-lock-screen.webp
---



> Steps to preform within live-boot Linux instance prior to installation


---


- [Settings Screen Saver][heading__settings_screen_saver]

- [Settings Lock Screen][heading__settings_lock_screen]


---



## Settings Screen Saver
[heading__settings_screen_saver]: #settings-screen-saver "Settings Screen Saver"


Once the desktop is shown, select the `Menu` icon (lower left corner) and type _`Screensaver`_, then press the <kbd>Enter</kbd> key


{% include modules/includes-picture/picture.html name='settings-screen-saver' %}


______


## Settings Lock Screen
[heading__settings_lock_screen]: #settings-lock-screen "Settings Lock Screen"


Under `Screensaver settings` select `Never` within the drop-down


Under `Lock settings` turn **off** `Lock the computer when put to sleep`


Also under `Lock settings` turn **off** `Lock the computer after the screensaver starts`


{% include modules/includes-picture/picture.html name='settings-lock-screen' %}


**[Next Page][next__page]**


[next__page]: {{ 'virtual-box/install-linux-to-usb' | absolute_url }} "Directions to follow within live-boot instance to install Linux to USB"

