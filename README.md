# BlurPlease

## About
Magisk module to disable MIUI's low RAM check and get back features such as:
- Background blur in notification shade (hence the name)
- Split screen with two apps
- Long press an app in recents for extra features
- Maybe more?

## Supported devices
The module has been tested on Redmi Note 9S (`curtana`) with MIUI `V13.0.2.0.SJWEUXM` (Android 12), but it should work with any Xiaomi device that has the low end configuration enabled.

If you're not sure whether Xiaomi considers your device as low end, connect the device to your PC and run the following command:

`adb shell getprop ro.config.low_ram.threshold_gb`

If your device has the amount of RAM specified in the output (in GBs) or less, you have low RAM mode enabled. This module sets this prop to false to disable the check entirely.

## Download
You can download the module [here](https://github.com/LeddaZ/BlurPlease/releases/latest).

## Credits
[Zackptg5](https://github.com/Zackptg5) for the [MMT-Extended](https://github.com/Zackptg5/MMT-Extended) template.
