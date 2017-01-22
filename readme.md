TXOnlySerial
========

This is a transfer-only serial library, which is software driven (bit-banging). In fact, it has been derived from the SoftwareSerial library by simply deleting all the receive methods (including the interrupt handling). It is very useful, when you want to get some debug output, for instance. It uses just one pin, which can be freely defined and it uses less memory than the SoftwareSerial library. Compared to SoftwareSerial, you save roughly 900 bytes flash and 80 bytes RAM.

Usage is very similar to SoftwareSerial, except that you use only one argument when creating an object, namely, the TX pin.

