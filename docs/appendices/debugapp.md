# Appendix E: The Maxtouch Debug App

## The Microchip ATMXT1066TD

Trackpad tracking is quite a tricky thing to do. In the Ploopy Trackpad, the chip that we use to perform the tracking calculations is the **Microchip ATMXT1066TD** (which we'll call the **MXT1066** for the rest of this document).

The MXT1066 is a highly-advanced chip with many, many, *maaany* features. It has so many features that it's hard to keep track of them all.

To alter them quickly and see the effects that the alterations have, [George Norton's Maxtouch Debug utility](https://github.com/george-norton/maxtouch-debug/) is extremely useful. It looks something like this:

![](../img/debug.png)


## Debug firmware

In order to use the debug app, you'll need to flash the `debug` firmware onto the Trackpad, available [here](https://github.com/ploopyco/trackpad/blob/main/ploopyco_pavonis_debug.uf2).

If necessary, follow the guide in [Appendix D](programming.md) to put new firmware onto the Trackpad.


## Putting the Ploopy Trackpad into bootloader mode while using the `debug` keymap firmware

Putting the Ploopy Trackpad into bootloader mode while using the `debug` firmware is very easy. Just put all five fingers down on the trackpad surface at once! The computer should state that your Trackpad was disconnected, and that a mass storage device was just plugged in. Once this is done, you should be able to drag and drop files onto the Ploopy device, as if the board was a USB drive.


## How to use it, though?

This, unfortunately, is the tricky part. Microchip places the documentation for the MXT1066 under NDA, which means that we are unable to share our copy with you. However, if you have a Microchip account, you can download the documentation for yourself quickly and easily.

The MXT1066 documentation has a full explanation of all of the features that are broken out in the debug utility.

Alternatively, you could just try changing things and see what happens...!