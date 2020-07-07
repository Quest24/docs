The Sonoff Mini is, as the name implies, a very small device, designed to be hidden where there's only supposed to be cables. Since it's not supposed to be visible, it's also designed to easily attach an external button. WATCH OUT!. There is no galvanic isolation in the power supply as the Sonoff Basic. All 3.3 volt electronics is connected directly to the main power!

Tasmota can be flashed on this device via OTA using the [Sonoff DIY](../Sonoff-DIY.md) feature.

Several free GPIO are available. The OTA jumper pin is the most accessible and very easy to use on a pin header.

![PCB with GPIO's etc labelled](https://user-images.githubusercontent.com/3912017/66733148-dfc3d300-ee5e-11e9-8715-87c8ecb844a7.jpg)

GPIO|Description
:-:|-
0|Button
1|TX
2|Available
3|RX
4|S2 (external switch input)
12|Relay and red LED
13|Blue LED
16|OTA jumper pin
GND|S1 (external switch input)
