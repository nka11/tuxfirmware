tuxfirmware
===========

New firmware for TuxDroid (more infos here: http://forum.tuxdroid-community.org/viewtopic.php?id=197)

Needs the AVR toolchain :
http://www.nongnu.org/avr-libc/user-manual/install_tools.html

debian/ubuntu/mint AVR Howto :

AVR toolchain stands in main repository, simply type :

    apt-get install gcc-avr avr-libc

    binutils-avr amd64 2.20.1-3 [4 595 kB]
    gcc-avr amd64 1:4.7.2-2 [13,3 MB]    
    avr-libc all 1:1.8.0-2 [5 766 kB]

Compile firmwares :

    cd tuxaudio
    make
    cd ../tuxcore
    make


