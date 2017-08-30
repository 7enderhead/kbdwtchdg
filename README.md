# kbdwtchdg
## Overview
A watchdog running [V-USB](http://www.obdev.at/vusb/) on an Attiny85 that identifies itself as a USB keyboard and sends keyboard strokes.

## What Can kbdwtchdg Do?

###WTCHDG Mode

In WTCHDG mode, kbdwtchdg listens for the capslock trigger to occur during WTCHDG_INTERVAL. If no trigger occurs, the text is written.
If a trigger occurs, the timer is reset.

###Non-WTCHDG Mode

After receiving the capslock trigger and waiting for DELAY time the text is written.

###Initial Writing

If first_start is set the text is written after INITIAL_DELAY after power up.

![state diagram](images/StateDiagram.png)

## How to Use
The repo contains an AtmelStudio 7 project file that is preconfigured for kbdwtchdg.

[Documentation can be found here.](http://kbdwtchdg.readthedocs.io)

## Acknowledgements
The code of this project is based on [Frank Zhao's USB business card](http://www.instructables.com/id/USB-PCB-Business-Card/) and built based on Dovydas R.'s circuit diagram for [usb_pass_input_with_buttons](https://github.com/Dovydas-R/usb_pass_input_with_buttons).
