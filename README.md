DRA8x8 Radio Module Arduino Library
======

**Incomplete**

This is a small library which handles the configuration of the Dorji DRA8x8 radio modules (DRA808M, DRA818V, DRA818U). The datasheet for these modules is somewhat lacking in details, and some quirks were discovered during testing.

To install, copy the DRA8x8 folder to your Arduino Libraries folder. You should then be able open Arduino and choose the "DRA818_Basic" example from the file mnu. 

Important Note: The DRA8x8 modules use 3V logic levels for IO. Most Arduino boards operate at 5V, and will need level conversion to connect to the modules safely. 
You can (as far as I've found) use 3.3V logic levels directly, and there are 3.3v Arduino clones available, such as the Seeduino.
