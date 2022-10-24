# marlin-config
hacky config for my modified ender3 pro

[Config examles](https://github.com/MarlinFirmware/Configurations) are used for the current config

# Ender Modifications
- [speeddrive](https://github.com/sashalex007/speedDrive)
- [BLTouch](https://www.creality3dofficial.com/products/creality-bl-touch)
- [Dual Z-Axis](https://www.creality3dparts.com/product/creality-dual-z-axis-upgrade-kit-with-lead-screw-and-stepper-motor-for-ender-3-3-pro-3-v2/)

# How to...
1. clone this repo
1. clone https://github.com/MarlinFirmware/Marlin into a different directory
1. copy over `Configuration*` into the `Marlin/Marlin`
1. check platformio.ini in `Marlin` with the examle in this repo
1. build with [Marlin auto build](https://marlinfw.org/docs/basics/auto_build_marlin.html)