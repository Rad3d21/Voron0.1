Ledmounts for the 8 RGB led PCB's from china.
They can be screwed down using m2.5 screws.
There is a solderhelper to help solder the 2 pcb's together with the right spacing.![image](https://user-images.githubusercontent.com/43404751/155505808-7ce055b3-048b-40a3-a440-aff7dccbbf32.png)

The wire to the DOUT is fed from the end to the beginning of the ledmount.
Tuck the wire under the incoming wire.
Beware ! First put on the endcap before soldering !
If you don't want the colors to be visisble you could add some black heatshrink also before soldering.
(or use a black marker or paint)

The connections are made to the neopixel 1 and neopixel 2 ports (4pin) on the umbilical PCB from timmit99
The ESP01 board is equipped with WLED and connected to neopixel in on the umbilical PCB.
The power can be pulled from the 5V/GND of the raspberry pi or directly from 5V.
In the WLED settings the number of leds is 32 and the segments are 1-16 and 17-32 with mirror checked on one.

The cables are pluggable to be able to take the backpanel off without disconnecting anything else.
The holes in the backpanel are big enough to pull the connectors through.
