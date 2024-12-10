# The Ploopy Trackpad

![The Ploopy Trackpad](trackpad.jpg)

By some stroke of luck, you've made your way here. The Ploopy Trackpad. Your life will never be the same.

This repository contains all of the design and production files necessary to make a Ploopy Trackpad. We've also included some kick-ass documentation on how to get it made, assemble it, and program it [which you can find here](https://ploopyco.github.io/trackpad/).

What are you waiting for? Your new life awaits.

## QMK?!

Kits bought from the [Ploopy store](https://ploopy.co/product-category/trackpad/) come with QMK and VIA preloaded. [Check out the documentation](https://ploopyco.github.io/trackpad/) for instructions on how to load new firmware onto your device. (It's super easy!)

The firmware for the Trackpad hasn't been merged into QMK at the time of this commit, so for now, [firmware can be found here](https://github.com/ploopyco/qmk_firmware/tree/multitouch_experiment).

The firmware hex file that ships with all Adepts is included in this repository as well, as `ploopyco_pavonis_default.uf2`.

## Under what license is this released?

As per QMK's licensing requirements, the firmware for the Ploopy Trackpad is released under GPLv3. Hardware design files, including electronics and mechanical files, are released under OHL CERN v2-S. Check the respective directories for full license text.
