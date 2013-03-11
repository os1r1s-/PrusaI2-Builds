Instructions for compiling Marlin on Arduino 1.x IDEs
=====================================================

You *must* copy the "pins_arduino.h" file from this directory to your {Arduino Root}\hardware\arduino\variants\mega\ folder in order for the SmartLCD controller to work. This updated pins file makes additional GPIO lines on the AtMega2560 available to the Arduino IDE.