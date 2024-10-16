# Appendix A: Printed circuit boards


## Buying boards from us
Getting the Ploopy boards made can be complex, and expensive, especially if you only need one set. [That's why we sell kits with everything you need to build a Ploopy Adept Trackball](https://ploopy.co/product-category/trackball/adept/). Here's why that's great for you:

- You get a PCB with all components soldered
- The firmware is already programmed on the microcontroller, so you won't have to program it
- It'll cost a hell of a lot less than if you do a production run of PCBs just for yourself
- You won't have to order components and wait while they come in
- We guarantee that it works

Just something to consider. You're smart. You'll figure it out.

## Making your own boards

Want to make your own Ploopy Adept Trackball boards? Great! Less work for us. Seriously, though, only choose this option if you know what you're doing. You don't want to embarrass yourself, do you?

### Step 1: Order the PCBs from a PCB production company

Here are the most important configurations you'll need to communicate to the company:

- 4 layers
- FR-4, TG 150-160 (basically, whatever the cheapest option is)
- 0.8mm thickness
- 6/6mil track/spacing distance
- 0.3mm minimum hole size
- ENIG surface finish, but you can go with HASL if you don't care about lead poisoning
- 1oz copper thickness for both outer and inner layers
- Choose whatever colours you want for solder mask and silkscreen; we like white solder mask and black silkscreen

If something is missing from here, it's not really important.

At some point, you'll have to upload design files to the production company. Use the [electronics source files](https://github.com/ploopyco/adept-trackball/tree/master/hardware/electronics) to generate manufacturing files (you'll have to convert them from their native Altium format if you're using some other platform). That should contain everything you need to get the boards made. If the production company rejects this package, however, you'll need to address the issue yourself.

### Step 2: Order the electronics components

All of the components are described in the schematics of the PCBs. Ordering the components is left as an exercise for the reader.

A complete list of all of the components can be found in the electrical design files.

### Step 3: Get the necessary tools

- PCB
- All of the electronics components
- A soldering iron
- Solder
- A printout of the schematics

### Step 4: Solder the components to the boards

Once you've got the PCBs and all of the components, print out the schematics. Use the schematics to match the reference designators on the PCBs to the reference designators on the schematics, and then get to soldering.

If you've never soldered surface mount components before, or want a refresher on how to solder, we recommend [this video on using an iron to solder surface mount components](https://www.youtube.com/watch?v=3NN7UGWYmBY), and [this video on using a hot-air soldering station](https://www.youtube.com/watch?v=c_Qt5CtUlqY).

Lastly, you'll need to follow a set of special instructions to assemble the PMW3360 sensor and the optic. [Take a look at page 11 of the official PMW3360 datasheet to find out how to do this](https://d3s5r33r268y59.cloudfront.net/datasheets/9604/2017-05-07-18-19-11/PMS0058-PMW3360DM-T2QU-DS-R1.50-26092016._20161202173741.pdf) (page 8 has visuals, for those of you who like purdy pictures).

**MAKE SURE THAT THE PMW3360 IS ORIENTED CORRECTLY BEFORE YOU SOLDER IT!** This is a really easy step to mess up, so *DOUBLE-CHECK IT!*

### Step 5: All done!

Congrats, you finished assembling the electronics! Pat yourself on the back.