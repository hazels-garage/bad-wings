<a href="https://shop.hazel.cc/products/bad-wings-v2-1">
<img src="https://img.shields.io/badge/-Purchase-%23000?style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAAABGdBTUEAALEQa0zv0AAAACBjSFJNAACHDwAAjA8AAP1SAACBQAAAfXkAAOmLAAA85QAAGcxzPIV3AAABCGlDQ1BJQ0MgUHJvZmlsZQAAKM9jYGBckZOcW8wkwMCQm1dSFOTupBARGaXAfoeBkUGSgZlBk8EyMbm4wDEgwIcBJ/h2DagaCC7rgsxiIA1wpqQWJwPpD0Acn1xQVAJ0E8gunvKSAhA7AsgWKQI6CsjOAbHTIewGEDsJwp4CVhMS5Axk8wDZDulI7CQkNtQuEGBNNkrORHZIcmlRGZQpBcSnGU8yJ7NO4sjm/iZgLxoobaL4UXOCkYT1JDfWwPLYt9kFVaydG2fVrMncX3v58EuD//9LUitKQJqdnQ0YQGGIHjYIsfxFDAwWXxkYmCcgxJJmMjBsb2VgkLiFEFNZwMDA38LAsO08APD9Tdt4gbWmAAAACXBIWXMAABJ0AAASdAHeZh94AAABC0lEQVQ4T2MAgv9kYqyCxGBMQUtFVwwxLBhVwEDG+n934PL/HQFLUMSxYEzBJp85/8td+/97aUf9jzcv+s/HIQgWZ2JkQlaH0MDOwgG2rcJtAhjXek773+G/+D8POz9QEzOyJhBGcMwVnf83es+GawThNr8FYDlGBka4OihGcEzlHcEaS1x6wJoq3Sf9L3PtQ1aMjBEcNTH9/xoShv9jzPL/13lOB2tKta76b6vihawBhhEcER7J/yxMrECF3v8TLEr+V7lP/t/qu+C/grAGsgYYRhUABUiD10ywJpCtDV6z/ksLKKKogWJUgXb/RcAAWQjEi/6HG2dhC00YxhTkZOXGEMOCsQoSwAz/AUZL+dIX/BrCAAAAAElFTkSuQmCC" />
 </a>
<a href="https://discord.gg/jP6hvgNN8r">
  <img src="https://img.shields.io/discord/989552667330228374?color=%237289da&label=%20&logo=discord&logoColor=%23fff&style=flat-square" />
</a>

# Bad Wings v2
![Bad Wings v2](images/bad-wings-v2-no-cirque.jpg)

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
      * note: The blue tape side of the cable should face away from the center of the cirque
    * Insert Cirque into housing
      *  Correct orientation should have the ribbon connector facing the thumb switches, and be right over the hole in the PCB
      * A dab or two of hotglue on the underside will help keep it in place.
    * Run FPC cable through Switchplate/PCB
    * Connect FPC to PCB
      * note: the blue tape side of the cable should be facing away from the PCB
* [Flash Firmware](firmware/README.md)
* Insert PCB into bottom case
* Use 8mm countersunk screws through bottom of case into PCB
    * If Cirque, use 12mm countersunk screws to attach housing
* Apply rubber feet to bottom of case
* Enjoy!

