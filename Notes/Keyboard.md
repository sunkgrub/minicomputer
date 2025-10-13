# KeyBoard Notes

## Warnings on hotplugging
Apparently it is very dangerous for the computer to plug in a PS/2 device while the device is on, therefore we should apply some preventative measures like a fuse

## Clock
- Must be 50 MHz, should be kept in mind when selecting our micro controller.

## Sending Data
The general format for the protocol is an 11 bit signal. These 11 bit signals send 1 byte at a time. 

- 1 start bit.  This is always 0.
- 8 data bits, least significant bit first.
- 1 parity bit (odd parity).
- 1 stop bit.  This is always 1.

Odd parity means that the total number of bits in the signal must be odd. Each bit is sent over one clock pulse length

