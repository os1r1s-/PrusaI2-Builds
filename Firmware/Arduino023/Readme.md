Instructions for compiling Marlin on Arduino023 IDEs
====================================================

You *must* copy the "pins_arduino.c" file from this directory to your {Arduino Root}\hardware\arduino\cores\arduino\ folder in order for the SmartLCD controller to work. This updated pins file makes additional GPIO lines on the AtMega2560 available to the Arduino IDE.