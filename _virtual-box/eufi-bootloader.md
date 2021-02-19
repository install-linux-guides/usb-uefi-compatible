---
title: EUFI Bootloader
description: Configuring bootloader for booting from USB Grub2 before built-in drive of host
date: 2021-02-14 09:00:00 -0700
# date_updated:  # Optional and formatted like 'date' above
time_to_live: 1800
layout: post
---



Use <kbd>Left</kbd>(<kbd>&larr;</kbd>)/<kbd>Right</kbd>(<kbd>&rarr;</kbd>) arrow keys on keyboard to select `Boot` _tab_


Use <kbd>Up</kbd>(<kbd>&uarr;</kbd>)/<kbd>Down</kbd>(<kbd>&darr;</kbd>) arrow keys on keyboard to select `File Browser Add Boot Option`


Within `Select Media` menu select the target USB drive, eg. `USB: Ultra Fit`


Within `Select Media File` menu select `<EFI>`


- If **not** using Secure Boot on host select `grubx64.efi`

- If using Secure Boot select `shimx64.efi`


> Note, I have yet to test Secure Boot option but according to Internet `shimx64.efi` _should_ be the correct option


A _window_ should pop-up requesting a _name_ for the entry, type in something descriptive eg. `Mint19` then press <kbd>Enter</kbd> key


The `Boot` _tab_ should re-appear, use <kbd>Up</kbd>(<kbd>&uarr;</kbd>)/<kbd>Down</kbd>(<kbd>&darr;</kbd>) arrow keys to select the `Boot Option #<n>` that was just named, then use the <kbd>Space</kbd> key to raise priority to the top of the list


Look for directions near top or bottom of screen such as _Press <kbd>F10</kbd> to Save & Exit_, and press that function key

