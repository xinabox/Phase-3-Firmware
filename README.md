# Phase-3-Firmware

This firmware only supports the [CC03](https://wiki.xinabox.cc/CC03) used in the [ThinSat Program](http://www.vaspace.org/index.php/thinsat-program).

## Flashing
In order to get the firmware on to the CC03, follow these instructions:
* Connect the CC03 to the IP03, using both the normal connector and the small connector.
* Connect the IP03 using a micro-USB to USB-A cable, a normal micro-USB cable
* Insert the connected USB cable into a computer running Microsoft Windows or into an Apple Computer
* Download the .uf2/.zip file from here
* Eventually unpack the .zip file to expose the .uf2 file
* Double-click the button on the IP03 to place the CC03 in programming mode.
* The CC03 is in programming mode if the blue LED fades in and out.
* Drag and drop the .uf2 file to the disk named CC03.
* Re-install the CC03 into the satellite circuit.

## xChip Sensors supported
- [CC03](https://wiki.xinabox.cc/CC03) ATSAMD21G18  w/Temperature sensor
- [SL19](https://wiki.xinabox.cc/SL19), IR Temperature 
- [SL01](https://wiki.xinabox.cc/SL01), UVA, UVB, Light Sensor: Advanced Light Sensor
- [SW10](https://wiki.xinabox.cc/SW10), Temperature Sensor
- [SI01](https://wiki.xinabox.cc/SI01), IMU 9DoF w/Temperature sensor
- [MN01](https://wiki.xinabox.cc/MN01), ThinSat™ Payload Interface
- MN02 ThinSat™ Payload Interface w/Temperature sensors
