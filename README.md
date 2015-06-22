#Mojo Bootloader
This is the Arduino compatible bootloader that ships preloaded on the AVR on the Mojo V3.

It is a slightly modified version of the bootloader for the Arduino Leonardo.

To build the bootloader for the ATmega32U4 (Mojo V3 and some V2) use Makefile-v3 (the default). To build the bootloader for the ATmega16U4 (Mojo V2) copy Makefile-v2 to Makefile and run make.

##Hex Files
###mojo-vX-Caterina.hex
This is only the bootloader.
###mojo-vX-loader.hex
This is the default FPGA loading program only.
###mojo-vX-init.hex
This is the full bootloader+loader and is what we program to new Mojos.
