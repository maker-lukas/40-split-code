e# 40%-ish Split Keyboard

This custom split keyboard runs [RMK](https://rmk.rs), a modern and powerful firmware that supports flexible layouts and advanced features. It also has full support for **Vial**, enabling real-time key remapping and customization without needing to recompile firmware.

## Features

* **RMK Firmware** – Lightweight and modular firmware designed for custom keyboards
* **Vial Support** – Modify keymaps on the fly through a user-friendly GUI
* **Split PIO Support** – Uses RP2040's Programmable I/O to handle split communication cleanly
* **4 Layers** – Plenty of flexibility for productivity, gaming, or layered macros
* **Powered by RP2040** – Fast dual-core microcontroller with ample I/O and memory

## Configuration Files

These config files define the keyboard layout and Vial settings:

|                                                    `keyboard.toml`                                                   |                                                    `vial.json`                                                   |
| :------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------: |
| ![keyboard.toml](https://hc-cdn.hel1.your-objectstorage.com/s/v3/98f504a70032b6d848b211c3fafb91cf4f7fc346_image.png) | ![vial.json](https://hc-cdn.hel1.your-objectstorage.com/s/v3/72a8afddf7274b5197b4d6f9f48dc510f2aff4da_image.png) |

---

## Vial Interface Example

This is what it looks like inside the Vial app once your board is recognized:

![vial](https://hc-cdn.hel1.your-objectstorage.com/s/v3/665ba123b927464b97aa57cfbc3024b7c9c45a49_image.png)

---

## Keyboard Hardware

This build is based on the open-source [40%-ish Split Keyboard by capitaoananas](https://github.com/capitaoananas/40-ish-split-keyboard). It’s a compact layout with just enough keys for productivity while keeping your desk clean and your fingers closer to home row.

---
