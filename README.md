## Adafruit DS3502 I2C Digital 10K Potentiometer  PCB

<a href="http://www.adafruit.com/products/4286"><img src="assets/4286.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit DS3502 I2C Digital 10K Potentiometer . 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4286

### Description

If you're a person like me that gets exhausted turning knobs all day, the DS3502 is just the ticket to calm all your knob-turning related troubles. Instead of having to _turn knobs_ with your _HANDS_ like an _ANIMAL_ the DS3502 I2C Digital Potentiometer allows you to let your microcontroller adjust the resistance for you! Now you can free your hands to spin your fidget spinner or or eat a slice of pizza while you're on the phone. Talking over an I2C bus, your Arduino, CircuitPython board,  or Python powered computer can talk to the DS3502 and tell it to vary its resistance at your beck and call.

Working with the DS3502 is easy as an I2C controllable pie. We've  put it on a breakout PCB with the required support circuitry and [SparkFun qwiic](https://www.sparkfun.com/qwiic) compatible [STEMMA QT](https://learn.adafruit.com/introducing-adafruit-stemma-qt) connectors to allow you to use it with other similarly equipped boards **without needing to solder.** This handy little helper can work with 3.3V or 5V micros, so it's ready to get to work with a range of development boards. The DS3502 is a simple chip that does one thing well and so it's very easy to work with. Wire it up and set the value for the wiper, thats it. [To make things _even easier_ we've gone and written Arduino and CircuitPython/Python 3 drivers to simplify interfacing with your new knob-replacing friend.](https://learn.adafruit.com/ds3502-i2c-potentiometer/)

"OK, this thing sounds great. Give me some details" you say. OK then, here you go: The wiper value is a 7-bit number meaning there are **128** possible levels of resistance to choose, from **0-10K ohms.** You can even set a default value that will be set on power up. The analog voltage controlled can be from **4.5-15.5V**. Additionally you can use the address jumpers or pins to set the I2C address to one of four values, allowing you to have four DS3502s on the same I2C bus.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Kattni Rembor for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
