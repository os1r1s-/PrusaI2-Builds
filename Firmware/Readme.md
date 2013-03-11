Prusa Build Arduino Notes
=========================

In order to get the SmartLDC control panel working, you MUST swap out the pins_arduino.h or the pins_arduino.c file, depending on which IDE you're using.  If you're using Arduino 023, use the pins_arduino.c file located in the Arduino023/ folder.  If you're using Arduino 1.x, use the pins_arduino.h file located in the Arduino_1.x/ folder.  These changes are necessary per the instructions located here: http://reprap.org/wiki/RamboLCD