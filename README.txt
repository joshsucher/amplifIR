amplifIR retrofits an old amp (in my case, a Yamaha A-760 from c1981) with an infrared sensor and an Arduino, controlling a servo (to push the power button) and a motorized pot (to rotate the volume knob) housed within the unit.

A full writeup can be found here: http://www.thingswemake.com/amplifir/

Inspired by Ian Johnston, whose more elegant & compact solution, built for a Pioneer amp, can be found here: 
http://www.ianjohnston.com/index.php?option=com_content&view=article&id=91

Hardware used:

- Arduino Uno
- Bourns PRM162-K415K-104A2 motorized potentiometer
- Hitek HS-311 servo
- Seeeds motor shield

Code used:

- Ian Johnston's Pioneer amp volume controller (http://www.ianjohnston.com/index.php?option=com_content&view=article&id=91)
- Seeed motor shield library (http://www.seeedstudio.com/wiki/Motor_Shield_V2.0)
- IRremote library (https://github.com/shirriff/Arduino-IRremote)
- Arduino IDE servo library "sweep" example (http://arduino.cc/en/Tutorial/sweep)
- Watchdog reset (http://www.xappsoftware.com/wordpress/2013/06/24/three-ways-to-reset-an-arduino-board-by-code/)