# Bad Wings: Slim
Ultrathin, wireless Bad Wings.

![Bad Wings: Slim - top view](images/bad-wings-slim-top.jpg)
![Bad Wings: Slim - side view](images/bad-wings-slim-side.jpg)


# Features
* 36 key, Kailh XSwitches.
* Less than a cm tall.
* Bluetooth via XIAO BLE
* CR2032 Battery
* [Open Source](source/)
* [Gerbers](source/GERBER-bad_wings_slim.zip)

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

## SUPPORT
<a href='https://discord.gg/jP6hvgNN8r'>
<img src="https://discordapp.com/api/guilds/989552667330228374/widget.png?style=shield" alt="Discord Shield"/>
</a>


---
<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1">

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/jasonhazel/kurp">Bad Wings: Slim</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/jasonhazel">Jason Hazel</a> is licensed under <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY 4.0</a></p>
