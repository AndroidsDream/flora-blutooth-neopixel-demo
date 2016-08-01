# flora-blutooth-neopixel-demo
Working code for anyone who wants to use their Adafruit Flora (and Bluefruit LE module!) with the provided app. No modifcations should be nessary.

This code runs properly on the Flora v2. With minor modifcations it should run on the v1, likely just the pin number might need to be changed. It should run on the v3 with no modifications. 

My set up uses the Flora Wearable Bluefruit LE Module (PRODUCT ID: 2487). It should work with other Bluefruit products, but I haven't been able to try that.

-----

Make sure everything is hooked up properly. (Crude diagram below for reference.)

(Flora)       (Bluetooth)
GND ----------- GND
RX ------------ TX
TX ------------ RX
3.3 v --------- 3.3 v

Bluetooth module must be in command mode, it will ask you to switch to data mode when appropriate.

This code only runs properly when hooked up to a computer via USB, and running the Serial Monitor.


