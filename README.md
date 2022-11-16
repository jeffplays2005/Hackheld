## Hackheld

A open source hackable handheld for DIY.

## Hackheld Joystick

![Hackheld Joystick](https://raw.githubusercontent.com/jeffplays2005/Hackheld/main/Hackheld_Joystick_Images/Front_with_components.jpg)

**DISCLAIMER:** I haven't yet built a real one of these so please be aware that this project may not work! Do this at your own risk. I will update this repo when I have built mine. There is also no 3d print case although I assume you can design one yourself. The screw holes are 2.053mm thick in diameter. It is also my first PCB project so if anything goes wrong, please help!

This is a redesign of SpaceHuhn's Hackheld Vega but with a 5 direction switch and a smaller board.

It can run the [ESP8266 Deauther](https://github.com/spacehuhntech/esp8266_deauther), but you can also write your own firmware using Arduino.

### DIY this project

[Download Gerbers For Single Board](https://github.com/jeffplays2005/Hackheld/raw/main/Hackheld_Joystick_PCB/Hackheld_Joystick_Gerber_v2.0.1_single_board.zip)

[Download Gerbers For Double Board Single Sheet - you can print two boards on a single sheet!](https://github.com/jeffplays2005/Hackheld/raw/main/Hackheld_Joystick_PCB/Hackheld_Joystick_Gerber_v2.0.1_double_board.zip)

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
Original Hackheld by SpaceHuhn: https://github.com/SpacehuhnTech/Hackheld *Inspiration + original creator!*
DSTikes hackheld schematics: https://github.com/lspoplove/Deauther-Project *Found it difficult checking the RGB light traces and looked in the schematics*
ItsKarilito: https://github.com/ItsKarlito/Hackheld *Redesigned the pcb and fixed some errors, this helped me trace where the wires go*

### License

This is open source, just like the original hackheld!
