Packages for `avrdude` and required libraries for OpenWRT Barrier Breaker (14.07). Tested on a Raspberry Pi with an Arduino Uno.

Place the files in the OpenWRT filesystem (e.g. with `scp`) and install with:

    opkg install ./avrdude_5.11.1-2_brcm2708.ipk libncurses_5.9-1_brcm2708.ipk terminfo_5.9-1_brcm2708.ipk libusb-1.0_1.0.9-1_brcm2708.ipk libusb-compat_0.1.4-1_brcm2708.ipk libreadline_6.2-1_brcm2708.ipk libftdi_0.20-1_brcm2708.ipk ./librt_0.9.33.2-1_brcm2708.ipk libpthread_0.9.33.2-1_brcm2708.ipk
