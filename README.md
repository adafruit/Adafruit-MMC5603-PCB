## Adafruit MMC5603 Triple-axis Magnetometer PCB

<a href="http://www.adafruit.com/products/5579"><img src="assets/5579.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit MMC5603 Triple-axis Magnetometer. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5579

### Description

Sense the magnetic fields surrounding us with this handy triple-axis magnetometer (compass) module. Magnetometers can sense where the strongest magnetic force is coming from, generally used to detect magnetic north, but can also be used for measuring magnetic fields. This sensor tends to be paired with a 6-DoF (degree of freedom) accelerometer/gyroscope to create a 9-DoF inertial measurement unit that can detect its orientation in real-space thanks to Earth's stable magnetic field. It's a great match for the LSM6DSOX from ST!

We based this breakout on the MMC5603, a great general purpose magnetometer with a very wide range and bot I2C and SPI interfaces. This compact sensor uses I2C to communicate and it's very easy to use. Simply download our library and connect the SCL pin to your I2C clock pin, and SDA pin to your I2C data pin and upload our test program to read out magnetic field data. If you'd like, you can also use SPI to receive data (we just happen to prefer I2C here)

This sensor can sense ranges from ±30 Gauss (±3000uT or ±3mT) with no range-setting required and full 20 bit output up to 1000 Hz rate reading. The range makes it good for reading Earth's magnetic field (which maxes at about 0.6 Gauss) or some basic magnets. It isn't good for very strong rare earth magnets, for that check out the TLV293.

To make life easier so you can focus on your important work, we've taken the MMC5603 and put it onto a breakout PCB along with support circuitry to let you use this little wonder with 3.3V (Feather/Raspberry Pi) or 5V (Arduino/ Metro328) logic levels. Additionally, since it speaks I2C you can easily connect it up with two wires (plus power and ground!).  We've even included SparkFun qwiic compatible STEMMA QT connectors for the I2C bus so you don't even need to solder! Just wire up to your favorite micro and you can use our CircuitPython/Python or Arduino drivers to easily interface with the LIS2MDL and get magnetic measurements ASAP.

It's fully assembled and tested.  Comes with a bit of 0.1" standard header in case you want to use it with a breadboard or perfboard.  Four 2.5mm (0.1") mounting holes for easy attachment.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
