# Chimera Laser Cutter Control

**Responsible Adult**: [Randy Hall](https://github.com/randybuildsthings)

This Chimera project provides the project (circuit board, bill of materials, etc.) to provide a Mach3/LinuxCNC capable controller board to drive the laser + the stepper motors that position the cutting beam.

This project borrows *heavily* (read: hours of looking over a PDF schematic) of the very excellent but out-of-stock Laser Cutter Converter board that Chris Jones of [Chris' Circuits](http://www.chriscircuits.com) successfully made and then sold out of repeatedly thanks to Hack-A-Day in 2013.

Well, it's almost 2015 and he doesn't seem to be making it any more. Enter the Chimera!

## Ew, EAGLE CAD

Yeah, it's EAGLE CAD. This design works entirely in their free tier, using just two layers and within the size constraints. We might consider moving it to KiCAD or another PCB layout tool, but for now, it's this.

This project was built from scratch using EAGLE CAD 7. We don't expect that it will work on previous version of the program.

## But, what do I do with this?

Ultimately, we will provide packaged and tagged releases of the Gerber and Excellon files for a given revision. Then you can take those files to your favorite PCB fab and get them made.

For now, you can load up whatever version of EAGLE CAD you can find, and open the `.SCH` and `.BRD` files into the software. Behold! The masterpiece. Now you can use the CAM batch tool to create the Gerber and Excellon files.

Step three... PROFIT!

## Warranty

*There is none.*

If you build and use this board and it burns down your laser cutter, your house, your RV, your office building, or the whole neighborhood, **it's on you bro.** If you don't accept this, then don't use this design. Otherwise, experiment wisely and always have a fire extinguisher handy. And an emergency power shutoff wouldn't hurt either.

The good news is we've now open sourced it, so knock yourself out! (*Note: any reference to knocking oneself out is said here only in jest, and neither Chimera Art Space or the author take any responsibility for anyone who actually takes the imperative literally, thereby effecting blunt force trauma on themselves causing loss of consciousness. This message will self-destruct whenever we get around to editing the Markdown to remove it*)