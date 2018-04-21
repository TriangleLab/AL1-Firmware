# AL1 QMK Firmware 

## Building Guide

- Step 1: Follow the tutorial [here](https://docs.qmk.fm/install-build-tools) and install all the dependencies. 
- Step 2: Run `make al1` under the `AL1-Firmware` directory. You will find the .hex files in the same directory. 

## Flashing Firmware

- Follow the instructions [here](https://docs.qmk.fm/flashing-firmware)

## Making Changes on the Layout/Keymap

- There are two keymaps in `AL1-Firmware/keyboards/al1/keymaps/`.  The default layouts are: 

![Default kaymaps](https://i.imgur.com/g8zDjMH.png)

- In order to make changes base for the default layout, you need to edit the `keymap.c` files. 

- Example: If you want to change the `Insert` key to `Page Up` key in the default kemap, you can do it by changing `KC_INS` to `KC_PGUP` in line 5. 

- Find all the keycodes [here](https://docs.qmk.fm/keycodes). 
