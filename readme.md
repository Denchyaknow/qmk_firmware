# Denchos Fork of Quantum Mechanical Keyboard Firmware

[![Current Version](https://img.shields.io/github/tag/qmk/qmk_firmware.svg)](https://github.com/qmk/qmk_firmware/tags)

Leaving notes here for myself cause ill probably forget how to do anything in the future.

I made a custom workflow that should recreate my keyboards firmware with the updated keymapping pulled from [QMK Configurator](https://config.qmk.fm/#/mechboards/sofle/pro/LAYOUT)

To update my keyboard layout:

1. Get the current layout from this repo at qmk_firmware\keyboards\mechboards\sofle\pro\keymaps\dencho_keymap\layout.json
2. Upload that layout.json file to the web app [QMK Configurator](https://config.qmk.fm/#/mechboards/sofle/pro/LAYOUT) via the nifty buttons
3. Edit the keymap to w/e you want
4. Download the KeymapJson, no you dont need to compile it.
5. Push the new keymap.json as the updated layout.json file at  qmk_firmware\keyboards\mechboards\sofle\pro\keymaps\dencho_keymap\layout.json
6. Boom the custom workflow should handle the rest and publish a release with the update firmware for my baby keyboard.


Example QMK Config Output if flashed correctly:

![image](https://github.com/user-attachments/assets/ef276395-f847-4f9a-9645-94bf87f259bd)


Keep in mind you gatta do the old ONNNNE, One Two, One Two Three, One Two, Dance with the Reset button cause it never works the first time, and wait 10 secs between tries of putting it into DFU.
