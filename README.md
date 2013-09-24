atmega
======

ATmega breadboard library for Arduino 1.5 IDE

I created this hardware definition for the Arduino 1.5 IDE becuase I could not find anything that worked.  I have many ATmega8 chips that I like to breadboard with and the Arduino IDE is convenient to use even without the fancy bootloaders.  To use, place the atmega directory inside the Arduino hardware directory.  On a Mac, this is located at ~/Documents/Arduino/hardware.

Restart the Arduino IDE and you should see under Tools/Board a menu ATmega.  After selecting, then a Processor and Clock menu option should show up.

Many thanks to damellis/attiny for showing me a pattern to use for the new Auduino IDE configuration files.  The Arduino documentation is still a work-in-progress IMHO.

This was tested with the 1.5.4 beta.
