# AL1 QMK Firmware 

## Building Guide

- Step 1: Follow the tutorial [here](https://docs.qmk.fm/install-build-tools) and install all the dependencies. 
- Step 2: Run `make al1` under the `Al1-QMK-Firmware` directory. You will find the hex files in the same directory. 

## Flashing Firmware

- Follow the instructions [here](https://docs.qmk.fm/flashing-firmware)

## Making Changes on the layout/keymap

- There are two keymaps in `keyboards/al1/keymaps/`.  The default layouts are: 

![Default kaymaps](https://i.imgur.com/mankBOm.png)

- In order to make changes base for the layout, you need to edit the `keymap.c` files. 

- Example: If you want to change the `Insert` key to `Page Up` key in the default kemap, you can do it by changing `KC_INS` to `KC_PGUP` in line 5. You can find all the keycodes [here](https://docs.qmk.fm/keycodes). 
