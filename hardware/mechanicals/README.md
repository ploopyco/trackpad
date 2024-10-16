## Only one file? Where are the parts?

The STEP/STL files contain all of the plastic parts in one file. Doing it this way preserves the assembly information, showing how the parts are supposed to fit together, as well as the expected clearances between parts. It also bundles all of the parts for a given revision together, so there's no accidental mixing of parts from different revisions.

## How do I print this?

You'll need to split the parts in the file up before you can print them. Most slicers can do this; if you have a compatible printer we recommend PrusaSlic3r, since that's the one we use in-house and have checked.

Note that submitting this file to some 3rd party print services will cause confusion, as they are expecting one body instead of many. To do this, you can use PrusaSlic3r to split the parts and then export each separately as an STL.

## How can I use the included .3mf file?

The .3mf file was generated using PrusaSlicer v2.5. The job was generated for Prusa i3 MK2S/MK3S/MK3S+ printers. It assumes the use of PLA that is printable at 200-230C. If you have that PrusaSlicer version, such a printer, and such filament, then you're in a lot of luck! We use a .3mf job that is very similar to this one to print these parts on our printing farm.

If you do not, then using the included .3mf file is likely going to cause you a lot of headaches. If this is the case, the included .3mf file should be considered **as a reference only**. If you use it at all, it is recommended that you look at it to see what kinds of print settings we use (gyroid infill, 0.3mm layer height, part orientation, etc.). However, you should use your own slicing software to generate the .gcode files for your printer.

## Why don't you include a .gcode file?

For your safety. Uploading a .gcode file onto a printer can be extremely hazardous if that .gcode file wasn't specifically generated for that printer. We don't want to come anywhere near that sort of scenario, so we are not going to upload a .gcode file.