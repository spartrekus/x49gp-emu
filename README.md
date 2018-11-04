# x49gp-emu
emulator for the HP49 (free source) using GTK

svn checkout https://svn.code.sf.net/p/x49gp/code/ x49gp-code


 apt-get install libgtk2.0-dev
 
 
 
 Edit FIRMWARE (optional):

The default firmware will be 4950_92.bin, for HPGCC3 development copy
49_hpgcc.bin in to x49gp and change FIRMWARE in the Makefile.

------------------------------------------------------------------------

Build:

cd x49gp
make
make sdcard
make config
 
 
The latest rom downloadable from here:

http://hpgcc3.org/downloads/newrplfw.bin

should run fine on x49gp.
