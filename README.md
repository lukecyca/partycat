partycat led controller
=======================

Partycat is a small ESP8266-based controller for WS2812 LED strips.

Features
--------

- Level-shifted GPIO pins, including one for a WS2812 strip
- A footprint that lets you solder the end of the strip right to the board
- WS2812 is on the I2S port, so it can use DMA using this hack (or the Arduino-compatible version)
- an auxiliary high-current PWM channel with a power MOSFET (I use this for white LED strips to make brighter white than the WS2812s can do on their own)
- Programming using a standard 6-pin FTDI cable (no onboard USB you wuss)


![It's Party Time](/itspartytime.png?raw=true "It's Party Time")

Illustration Credit: http://nedroid.com/2009/05/party-cat-full-series/

