First off. I'm not good at github stuff. Just trying to get something on there.
Tips and pointers are welcome.

Ledmounts for the 8 RGB led PCB's from china.
They can be screwed down using BHCS m2.5 x 6 screws.
There is a solderhelper to help solder the 2 pcb's together with the right spacing.!
https://github.com/Rad3d21/Voron0.1/blob/main/ledmount/jig-soldering.jpg

The wire to the DOUT is fed from the end to the beginning of the ledmount.
Tuck the wire under the incoming wire.
<B>BEWARE ! First put on the endcap before soldering !</B>
If you don't want the colors to be visisble you could add some black heatshrink also before soldering.
(or use a black marker or paint)
Front and back can be screwed on with BHCS m3 x 6

The connections are made to the neopixel 1 and neopixel 2 ports (4pin) on the umbilical PCB from timmit99
The ESP01 board is equipped with WLED and connected to neopixel in on the umbilical PCB.
The power can be pulled from the 5V/GND of the raspberry pi or directly from 5V.
In the WLED settings the number of leds is 32 and the segments are 1-16 and 17-32 with mirror checked on one.

The cables are pluggable to be able to take the backpanel off without disconnecting anything else.
The holes in the backpanel are big enough to pull the connectors through. https://github.com/Rad3d21/Voron0.1/blob/main/ledmount/IMG_20220122_170136.jpg

My first design in the pictures had a single screw holding endplates. v2 has better positioning of the LED-PCBs and 2 screws holding endplates. (This is untested version)

