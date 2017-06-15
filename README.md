# Arp-8
MIDI-to-CV arpeggiator

The Arp-8 is a MIDI to CV converter that can arpeggiate, syncing with either a MIDI clock, analog clock (+5v pulse), or
internal clock. The arpeggiation can be turned off to act as a simple single voice MIDI to CV converter.

*Installing firmware

Using a USB ISP, such as AVRISP2 or USBTINY, connect to the 2x3 headers on the bottom of the module. Make sure the pins are connected correctly (the bottom row should be labled "GND, MOSI, 5+"). When installing the new firmware, be sure to have a cable inserted into the "CLK" jack.

Fuses: EFUSE = 0x05;  HFUSE = 0xde; LFUSE = 0xff
