![GitHub](https://img.shields.io/badge/CC--BY--NC--SA-test?style=flat-square&logo=creativecommons&logoColor=ffffff&label=%20&labelColor=8CBA04&color=8CBA04)
<a href="https://shop.hazel.cc/products/bad-wings-slim">
 <img src="https://img.shields.io/badge/-Purchase-%23000?style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAAABGdBTUEAALEQa0zv0AAAACBjSFJNAACHDwAAjA8AAP1SAACBQAAAfXkAAOmLAAA85QAAGcxzPIV3AAABCGlDQ1BJQ0MgUHJvZmlsZQAAKM9jYGBckZOcW8wkwMCQm1dSFOTupBARGaXAfoeBkUGSgZlBk8EyMbm4wDEgwIcBJ/h2DagaCC7rgsxiIA1wpqQWJwPpD0Acn1xQVAJ0E8gunvKSAhA7AsgWKQI6CsjOAbHTIewGEDsJwp4CVhMS5Axk8wDZDulI7CQkNtQuEGBNNkrORHZIcmlRGZQpBcSnGU8yJ7NO4sjm/iZgLxoobaL4UXOCkYT1JDfWwPLYt9kFVaydG2fVrMncX3v58EuD//9LUitKQJqdnQ0YQGGIHjYIsfxFDAwWXxkYmCcgxJJmMjBsb2VgkLiFEFNZwMDA38LAsO08APD9Tdt4gbWmAAAACXBIWXMAABJ0AAASdAHeZh94AAABC0lEQVQ4T2MAgv9kYqyCxGBMQUtFVwwxLBhVwEDG+n934PL/HQFLUMSxYEzBJp85/8td+/97aUf9jzcv+s/HIQgWZ2JkQlaH0MDOwgG2rcJtAhjXek773+G/+D8POz9QEzOyJhBGcMwVnf83es+GawThNr8FYDlGBka4OihGcEzlHcEaS1x6wJoq3Sf9L3PtQ1aMjBEcNTH9/xoShv9jzPL/13lOB2tKta76b6vihawBhhEcER7J/yxMrECF3v8TLEr+V7lP/t/qu+C/grAGsgYYRhUABUiD10ywJpCtDV6z/ksLKKKogWJUgXb/RcAAWQjEi/6HG2dhC00YxhTkZOXGEMOCsQoSwAz/AUZL+dIX/BrCAAAAAElFTkSuQmCC" /></a>
<a href="https://discord.gg/jP6hvgNN8r">
  <img src="https://img.shields.io/discord/989552667330228374?color=%237289da&label=%20&logo=discord&logoColor=%23fff&style=flat-square" />
</a>

# Bad Wings: Slim
Ultrathin, wireless Bad Wings.

![Bad Wings: Slim - side view](images/bad-wings-slim-side.jpg)
![Bad Wings: Slim - top view](images/bad-wings-slim-top.jpg)


# Features
* 36 key, Kailh XSwitches.
* Less than a cm tall.
* Bluetooth via XIAO BLE
* CR2032 Battery
* [Open Source](source/)

# Materials
* 1x XIAO BLE
* 36x [Kailh XSwitch and Keycaps](https://mkultra.click/kailh-x-switches-and-keycaps/)
* 37x SOD-123 1N4148 Diodes
* 1x MSK-12C02 Power Switch
* 1x [CR2032 Battery Holder](https://www.aliexpress.us/item/2251832843180857.html)

# Build Guide
* Install Diodes
* Solder XIAO
  * Surface mounted on top of PCB
  * Solder BAT and NFC pads from back of PCB
* Flash [Firmware](FIRMWARE.md)
* Test matrix works 
  * use metal tweezers to short the connections for each switch on the PCB
* If matrix works, install switches
  * place the switches and then tape them in place
  * flip board over, solder switches
  * _I install the switches a column at a time but, you do you._
* Solder CR2032 holder
* Solder battery diode
* Solder Power Switch
* Insert Battery
* Done
