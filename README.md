pi-top_Glimmer  
==============

<img src="https://github.com/uChip/pi-top_Glimmer/blob/master/pi-top_Glimmer_front.png" alt="Accessory board for pi-top laptop or pi-topCEED" height="308" width="365">  
This repository contains the design files and write-up for pi-top_Glimmer.  

The pi-top Glimmer is an accessory board for the [pi-topCEED](https://pi-top.com/product/ceed).  It also fits the pi-top laptop.  The board reconstitutes the Raspberry Pi GPIO connector. Unlike the [pi-topPROTO](https://pi-top.com/buy/addon) the Glimmer places the connector optimally for connecting the ["T-Cobbler Plus - GPIO Breakout"](https://www.adafruit.com/product/2028) or the ["Pi Wedge"](https://www.sparkfun.com/products/13717).

<picture>

The board includes support for an IR Receiver (TSOP38238 or similar) for IR remote control of the pi-top.  An on board Arduino monitors the Raw, 5V and 3.3V voltage levels of the pi-top power supply to help detect if the supply is overloaded.

Finally, the board includes an 8x8 LED (single color on/off) array that is refreshed from the Arduino and controlled from the pi-top's Raspberry Pi.

The software folder contains an Arduino sketch that is source code for Arduino which can be changed and updated from the pi-top.

The board is built using a combination of through-hole and (larger scale) surface mount technologies and is reasonably easy to hand assemble. I created this board for a number of reasons; to more easily enable prototyping on the pi-top, to learn more about the pi-top's accessory buss, to teach myself KiCad, and to enable future projects I have in mind.  

I did it as a one off, but it seems to have some utility for classroom scenarios.  If there is interest I would be willing to make a manufacturing run of these as a product.

## Order PCBs  

You can order this PCB directly from OSH Park.  Click on the following link.  
  * pi-top Glimmer - https://oshpark.com/shared_projects/aFUNW4O5 

<img src="https://github.com/uChip/pi-top_Glimmer/blob/master/Top.png" alt="PCB Top" height="431" width="500">

<img src="https://github.com/uChip/pi-top_Glimmer/blob/master/Bottom.png" alt="PCB Bottom" height="431" width="500">

See the Bill of Materials (BOM) file in the repo Hardware folder for a parts list.  

## Status  
  * PCB has been checked against components and specs and is currently out for fab.  

## File Formats  

Hardware design files are in "KiCad EDA" .kicad_pcb and .sch formats (KiCAD version: (2017-05-14 revision 14bb238b3).  A free version of the software can be downloaded from kicad-pcb.org.  

The example code is in Arduino .ino format (text).  A free version of the Arduino software can be downloaded from www.arduino.cc.  

## Distribution License  

License:
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">pi-top Glimmer</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/uChip/pi-top_Glimmer" property="cc:attributionName" rel="cc:attributionURL">C.Schnarel</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
  


