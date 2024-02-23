# VIA-enabled keymap for Freebird60 by jsta

This file lives at: `keyboards/keebsforall/freebird60/keymaps/jsta`

## Setup (assuming Windows + WSL)

Install [QMK Toolbox](https://github.com/qmk/qmk_toolbox)

Install [QMK MSYS](https://github.com/qmk/qmk_distro_msys)

## Compilation

```shell
qmk compile -kb keebsforall/freebird60 -km via
```

## Flashing

1. Unplug the usb cable

2. (Re)Load up hex file in QMK Toolbox and tick Auto-flash

3. Hold down the Esc (top left) corner key and plug in USB, watch QMK Toolbox

4. Disconnect cable, reconnect

## Links

- [https://docs.qmk.fm/#/newbs_getting_started](https://docs.qmk.fm/#/newbs_getting_started)

- [https://keebsforall.com/blogs/tutorials-for-beginners/how-to-flash-pcb-keyboard-with-qmk](https://keebsforall.com/blogs/tutorials-for-beginners/how-to-flash-pcb-keyboard-with-qmk)
