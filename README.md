# kbdwtchdg
## Short definition
V-USB-based watchdog that identifies itself as a USB keyboard and sends keyboard strokes.

## What can kbdwtchdg do?
It sends a defined message via USB to the computer. It does that either after a specific period of time after being plugged in,
or after a capslock trigger (pressing capslock x times).

![state diagram](images/StateDiagram.png)

## How to use
The repo contains an AtmelStudio 7 project file that is preconfigured for kbdwtchdg. 

[Documentation can be found here.](http://kbdwtchdg.readthedocs.io)
