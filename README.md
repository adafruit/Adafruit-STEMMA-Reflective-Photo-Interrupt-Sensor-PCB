## Adafruit STEMMA Reflective Photo Interrupt Sensor - TCRT1000 PCB

<a href="http://www.adafruit.com/products/5913"><img src="assets/5913.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit STEMMA Reflective Photo Interrupt Sensor - TCRT1000. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5913

### Description

An optical reflective sensor is a composite electronic device with two elements - an IR LED and an IR photo-transistor. The IR LED blasts light, and when something bounces the light back to the photo-transistor, the transistor turns on and the amount of current flowing through it increases. This makes the sensor great at detecting when something is in front of the sensor: when nothing is there the IR light never gets reflected back and the transistor stays off.

We have two versions of this sensor that are 'breadboard' friendly, the ITR20001 and a chunky all-in-one Infrared Reflective Sensor, but both are tough to mount, and require wiring up with resistors to get working. To make usage super fast and no-soldering-or-breadboarding-required, the Adafruit STEMMA Reflective Photo Interrupt Sensor is ready to go out of the box.

Power it with 3 to 5V DC and read the signal off the output pin to quickly detect reflective surfaces. A green LED tells you that the board is powered,  and a red LED will light up to let you know when the phototransistor is activated. (Both LEDs can be disabled)

Onboard we have a TCRT1000 right-angle sensor module. A potentiometer allows adjustment of how bright the IR emitter is, turn it all the way down for about 1mA, turn it all the way up for about 100mA. Then the receiving phototransistor is biased with a 10K pullup. When no IR light is detected, the output signal pin is high. When IR is bounced back, the voltage will drop down towards 0V.

This board has a simple plug-and-play JST PH (2mm pitch) input connector for solderless use. For use with a CircuitPlayground or micro:bit, this JST to alligator-clip cable works best. Red is power, ground is black and signal is white. For use with a breadboard, try this JST to male/plug-header. (We also have a socket-header cable if you want)

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
