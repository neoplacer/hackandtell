This is the C++ code for an Arduino-based count-down timer. It displays a five minute countdown 
with big numbers on a TV screen. It uses Arduino TVOut library (see: http://code.google.com/p/arduino-tvout/ )
for PAL or NTSC composite video output. The time duration of the count-down can be changed in the source code.
When the count-down is over it presents a flashing message ("APPLAUSE") on the screen. In addition, a MOSFET can
be attached to a PWM-capable pin of the arduino. We use this to light a big "APPLAUSE" sign with several LEDs.

Apart from the count-down function the code implements a simple serial monitor and a message display.

The program has a graphical menu which is controlled by a classic digital joystick oder gamepad like those found on the Atari 2600 or those
for the Commodore 64. We use an ancient Competition Pro joystick.

