The HC-SR04 distance sensor has an output (trigger) from which a signal is sent and an input (echo) which receives the previously sent signal. The time between sending and receiving the signal is measured. Atmega32 is designed to convert this time into a distance of basically sound speed. The 16x2 LCD display shows the current value on the screen.
 
used libraries:

MrLcd/MrLCDmega32.h
https://electrosome.com/wp-content/uploads/2018/03/MrLCDATmega32.zip

avr/interrupt.h
https://github.com/vancegroup-mirrors/avr-libc/blob/master/avr-libc/include/avr/interrupt.h

util/delay.h
stdlib.h
