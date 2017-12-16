Thread USB Dongle
=================

This repo holds the designs for an IEEE 802.15.4 USB dongle that is compatible
with the thread networking stack and supported by [Openthread](https://github.com/openthread/openthread).
The dongle will run in NCP mode and be used on thread border routes.

Currently there are no readily available IEEE 802.15.4 USB dongles on the 
market for a reasonable cost, so we design this dongle to be minimalistic,
and our current plan is for it to only contain a USB connector, serial
to UART converter, and an 802.15.4 radio SoC.
