This is schematic and CAD files (kICAD 9) for a really cheap ByteBlaster clone found on ALiExpress that is based on a CH552G. According to AliExpress it supports 1.0V to 5.5V although I am not convinced as it does not use the voltage ref supplied by the 10 pin programming cable but uses 22R inline resistors on the programming pins to limit voltage/current.
I have not verified the capacitor values but 100nF is normal for IC smoothing, The smaller sized caps are probably 1-47nF for more high frequency smoothing.
I removed the CH552G to view the traces underneath. Not sure why they didn't use pins 7 & 8 for TX/RX.
It appears to be identical to the clone that was used by Downtown Doug Brown https://www.downtowndougbrown.com/2024/06/fixing-a-knockoff-altera-usb-blaster-that-never-worked/ where he replaced the firmware to allow it to function under Linux and stop Blue Screening under Windows.

