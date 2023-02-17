## Hackheld

A open source hackable handheld for DIY.

## Hackheld Altair

![Hackheld Altair](https://raw.githubusercontent.com/jeffplays2005/Hackheld/main/Hackheld_Altair_Images/Front_with_components.png)

**UPDATE:** No need to worry on this project failing to build as I have received the parts and have tested everything and can verify the PCBs are working fine. Although due to the updated removal of solder pads, I will have to reorder the PCBs and see if the manufacturers are able to create it without any problems. I will update this repo when finished.
**DISCLAIMER:** There is no 3d print case designed for this project yet. If you'd like to contribute, please feel free to!

This is a redesign of SpaceHuhn's Hackheld Vega but with a 5 direction switch and a smaller board.

It can run the [ESP8266 Deauther](https://github.com/spacehuhntech/esp8266_deauther), but you can also write your own firmware using Arduino.

### DIY this project

[Download Gerbers For Single Rectangular Board](https://github.com/jeffplays2005/Hackheld/raw/main/Hackheld_Altair_PCB/Hackheld_Altair_Gerber_v2.0.2_rectangular_board.zip)
[Download Gerbers For Single Rounded Board](https://github.com/jeffplays2005/Hackheld/raw/main/Hackheld_Altair_PCB/Hackheld_Altair_Gerber_v2.0.2_rounded_board.zip)

Note: removed double board as panelisation should be done instead. You can panelise the PCBs easily with EasyEDA or other alternatives. For a 100mm x 100mm PCB, you can fit 2 in a row and no more in a column. The dimensions of a single Hackheld in this project is 43.5mm x 53.5mm.

Also the only method I could figure out to remove those holes in the solder pads were making them microscopical, meaning that some pcb manufacturers may tell you that they have skipped or have a problem with this.

I highly recommend buying the exact same parts as the section down below as many manufacturers use different 5 directional switches and I've designed the routes according to the one thats listed.

I recommend JLCPCB as they have fast shipping, cheap options and have several discounts. PCBWay is also a good alternative.

### Parts

Everything is purchased from Aliexpress and have been carefully selected so they are the cheapest avaliable options for most people:

1.3" display(can alternate but ensure the pins are **VDD,GND,SCK,SDA**): https://www.aliexpress.com/item/4001145494936.html

D1 mini(can alternate but ensure that you are getting one with the correct dimensions): https://www.aliexpress.com/item/32816149164.html

WS2812B 5050 RGB LED: https://www.aliexpress.com/item/1005002653014067.html

6*6 buttons(4 pin): https://www.aliexpress.com/item/33046122537.html

5 direction button(not suitable for alternatives): https://www.aliexpress.com/item/33024133078.html

Simple soldering and wire cutters may be needed to solder on + make sure the parts fit(the pins might be too long).

### Credits
Original Hackheld by SpaceHuhn: https://github.com/SpacehuhnTech/Hackheld *Inspiration + original creator(of the firmware too)! Thx Stefan.*

DSTike hackheld schematics: https://github.com/lspoplove/Deauther-Project *Used schematics to view more detailed wiring*

ItsKarilito: https://github.com/ItsKarlito/Hackheld *Redesigned the PCB and fixed some errors on the original Hackheld*

### License

This is open source, just like the original hackheld!
