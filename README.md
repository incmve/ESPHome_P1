# esphome_p1

Custom component for Home Assistant that uses SoftwareSerial instead of UART, this way no extra hardware is needed to invert the signal.
Reads P1 from my KAIFA MA105C meter.
Forked from https://github.com/nldroid/CustomP1UartComponent and customized for my hardware

## Hardware

I used a Nodemcu and nothing more, connect the RX pin to D5
![nodemcu](https://github.com/incmve/ESPHome_P1/blob/master/docs/nodemcu.jpg)

## Schema
![Schema](https://github.com/incmve/ESPHome_P1/blob/master/docs/RJ11-pinout.png)

