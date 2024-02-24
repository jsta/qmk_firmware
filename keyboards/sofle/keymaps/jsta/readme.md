# VIA-enabled keymap for Sofle by jsta

This file lives at: `keyboards/sofle/keymaps/jsta`

## Setup (assuming Windows + WSL)

Install [QMK Toolbox](https://github.com/qmk/qmk_toolbox)

Install [QMK WSL]

## Development

Develop in WSL, push to GH

Pull to repo in QMK WSL before compiling

## Compilation

```shell
qmk compile -kb sofle/rev1 -km jsta
```

## Flashing

1. Unplug the usb and audio cables

2. (Re)Load up hex file in QMK Toolbox and tick Auto-flash

3. Hold down the top outside corner key and plug in USB to first side, watch QMK Toolbox

4. Repeat for other side

5. Disconnect all cables, reconnect

## Links

- [https://docs.keeb.io/reprogramming-encoders](https://docs.keeb.io/reprogramming-encoders)

- [https://docs.qmk.fm/#/newbs_getting_started](https://docs.qmk.fm/#/newbs_getting_started)

- [https://josefadamcik.github.io/SofleKeyboard/build_guide.html](https://josefadamcik.github.io/SofleKeyboard/build_guide.html)
