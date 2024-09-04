# Climate Display

[![CI](https://github.com/Qeteshpony/climatedisplay/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Qeteshpony/climatedisplay/actions/workflows/ci.yml)

![3D Render](https://qeteshpony.github.io/climatedisplay/3D/climatedisplay-3D_top.png)

[Hardware Documentation](https://qeteshpony.github.io/climatedisplay)

Complete overhaul of one of my earlier electronics projects! A display that is running here for years, back then made completely with THT components on a crude pcb. It shows the temperature and dew point for the room and outdoor sensors. 

I learned a lot about pcb design since then and was not happy with the look of the old device so I remade the whole device in a way that keeps the general look but a lot more fancy, moving everything but the display elements to the back of the board, adding a 3d-printed frame, replacing the barrel connector with USB-C and many more little things. 

The old version also had the digits of the displays backwards which didnt matter when I wrote the arduino script to run it. But now I want to use ESP-Home so they have to be wired correctly ;)

Every other dual-7-segment module is upside down so the decimal dot on the last digit in each row can be used as a ° symbol.

The original project was documented on my blog: https://electronics.qetesh.de/climate-display/