COMPONENTS USED:


1.	BREADBOARD:
Breadboard is a way of constructing electronics without having to use a soldering iron. Components are pushed into the sockets on the breadboard and then extra 'jumper' wires are used to make connections.

2.	RG1602 LCD DISPLAY:
16×2 LCD is named so because; it has 16 Columns and 2 Rows. Because our LCD is a 16*2 Dot matrix LCD and so it will have (16*2=32) 32 characters in total. 

3.	i2C ADAPTER MODULE:
The character LCD is ideal for displaying text and numbers and special characters. LCDs incorporate a small add-on circuit (backpack) mounted on the back of the LCD module. The module features a controller chip handling I2C communications and an adjustable potentiometer for changing the intensity of the LED backlight. This adjustment is made with a small screwdriver. An I2C LCD advantage is that wiring is straightforward, requiring only two data pins to control the LCD. Connecting the Arduino UNO to the I2C interface of the LCD requires only four connections. The connections include two for power and two for data. The chart below shows the connections needed. The Arduino module and editor do not know how to communicate with the I2C interface on the LCD. The parameter to enable the Arduino to send commands to the LCD are in separately downloaded LiquidCrystal_I2C library. 

4.	IR SENSOR:
There are two types of infrared sensors: active and passive. Active infrared sensors both emit and detect infrared radiation. Active IR sensors have two parts: a light emitting diode (LED) and a receiver. When an object comes close to the sensor, the infrared light from the LED reflects off the object and is detected by the receiver. Infrared Transmitter is a light emitting diode (LED) which emits infrared radiations called as IR LED’s. Even though an IR LED looks like a normal LED, the radiation emitted by it is invisible to the human eye. Infrared receivers or infrared sensors detect the radiation from an IR transmitter. IR receiver is a photodiodes and phototransistors. Infrared Photodiodes are different from normal photo diodes as they detect only infrared radiation. 


5.	ARDUINO UNO:
Arduino is a single-board microcontroller meant to make the application more accessible which are interactive objects and its surroundings. The Arduino Uno comes with USB interface, 6 analog input pins, 14 I/O digital ports that are used to connect with external electronic circuits. The software used for Arduino devices is called IDE (Integrated Development Environment) which is free to use and required some basic skills to learn it. It can be programmed using C and C++ language. The 6 analog pins are marked as A0 to A5 and come with a resolution of 10bits. These pins measure from 0 to 5V. 


