# Ducted-Evap-AC-Controller
Reverse engineering and ESPHome tests for a Ducted AC controller to replace an old analog BreezAir SensorTouch controller

I built this project to control a Braemer swamp cooler sold in Australia as Seely International.

The control package is built by a company called Tekelek Australia.

Tekelek offer 2 control buses. Analog (o-5v) and Digital.

My unit is analog so I did not do any reverse engineering on the digital side which looks to be a proprietary bus.

Unit uses a 5 pin Molex connector to connect the touch panel and the goal of this project was to replace the old controller with a newer ESP32 based LCD touch screen.

This will work with any Evaporative swamp cooler that is based on the Tekelek Tek7, Tek600 and Tek400 series control boxes.

My unit was a Seely International Braemar unit. 
