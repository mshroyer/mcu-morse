Morse Code for Microcontrollers
===============================

This is an Arduino sketch for the [Adafruit ItsyBitsy 32u4](https://www.adafruit.com/product/3677), which
provides encoding and decoding of Morse code over both the serial port and an emulated USB keyboard.

This code is based on [an earlier project](https://github.com/mshroyer/msp430-morse) that specifically targeted the TI MSP430 LaunchPad. This should still work on the MSP430 as well as other Arduino-compatible microcontroller boards, except that the keyboard functionality (if enabled) relies on specific features of the ATmega32u4.