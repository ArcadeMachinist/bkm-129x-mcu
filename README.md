# bkm-129x-mcu
BKM129X clone firmware.

Based on https://github.com/skumlos/bkm-129x-mcu
Adds RGB status LED output.

Red - card has power, but was never initialized by the PVM.

Yellow - card ok, but not selected as input.

Green - card ok, selected, sync on.

Blue - card ok, selected, sync off.

I have used SK6812 5050 LEDs, but you can use any you want.
