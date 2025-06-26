<a href="https://discord.gg/jP6hvgNN8r">
  <img src="https://img.shields.io/discord/989552667330228374?color=%237289da&label=%20&logo=discord&logoColor=%23fff&style=flat-square" />
</a>

# Bad Wings v2
![Bad Wings v2](images/bw2-dash.jpg)
_Build by Dash, via 40% discord_

Improves upon the original by ditching the XIAO and shift register for an onboard STM32 microprocessor, reducing the build time and simplifying kits.

## Features
* 36 key unibody split
* Choc spaced, column staggered layout
* Gentle splay on ring and pinky columns
* Onboard STM32F072
* Cirque touchpad support
* Built in mounting standoffs
* [3D Printed Case](case/)

## Build Summary
* Solder hotswap sockets
* Insert switches into switchplate
* Insert switches into hotswap sockets
* If Cirque
    * Use soldering iron to install heatset inserts into Cirque housing
    * Insert FPC cable into Cirque
      * note: The blue tape side of the cable should face toward from the center of the cirque
    * Insert Cirque into housing
      *  Correct orientation should have the ribbon connector facing the thumb switches, and be right over the hole in the PCB
      * A dab or two of hotglue on the underside will help keep it in place.
      * The ribbon cable can be bent (but not creased!) to tuck it inside the housing.
    * Run FPC cable through Switchplate/PCB
    * Connect FPC to PCB
      * note: the blue tape side of the cable should be facing away from the PCB
* [Flash Firmware](firmware/README.md)
    * PCBs are pre-flashed with VIAL, so this step is optional at this time.
* Remove orange stickers from PCB standoffs.
* Insert PCB into bottom case
* Use 8mm countersunk screws through bottom of case into PCB
    * If Cirque, use 12mm countersunk screws to attach housing
* Apply rubber feet to bottom of case
* Enjoy!

## Special Thanks
* GeorgeN for helping me get the cirque working in QMK.
* Sadek Baroudi for fingerpunch and cultivating a great community
