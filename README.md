# NavSpark Shield for Raspberry Pi

[![CERN OSHW licensed](https://img.shields.io/badge/license-CERN%20OHL%201.2-blue.svg)](./LICENSE.txt)

[NavSpark][NavSpark] is Arduino compatible microcontroller board that has built in satellite navigation ([GPS][GPS] by default, and some models add [GLONASS][GLONASS], [BeiDou][BeiDou], etc...).

This adapter board provides means to connect the NavSpark board to a Raspberry Pi / Raspberry Pi 2.

For one example usecase, could create [a local network NTP server with accurate statellite timing through GPS+1PPS][timing]

## PCB

Revision v1, the proof of concept looks like this:

![PCB Front][pcbfront]

![PCB Back][pcbback]

[NavSpark]: http://www.navspark.com.tw/ "NavSpark homepage"
[GPS]: https://en.wikipedia.org/wiki/Global_Positioning_System "GPS on Wikipedia"
[GLONASS]: https://en.wikipedia.org/wiki/Global_Positioning_System "GLONASS on Wikipedia"
[BeiDou]: https://en.wikipedia.org/wiki/BeiDou_Navigation_Satellite_System "BeiDou on Wikipedia"
[timing]: https://gergely.imreh.net/blog/2015/11/navspark-beidou-ntp/ "Dual Satellite NTP server with Navspark"


[pcbfront] ./images/navspark_rpi_shield_v1_front.png "PCB front rendering with Kicad"
[pcbback] ./images/navspark_rpi_shield_v1_back.png "PCB back rendering with KiCad"
