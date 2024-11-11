# teensy_xinput_modifications
Added the modified Xinput dependencies to be uploaded and used in plaformio. 

Following the example from this solution thread: 
https://community.platformio.org/t/how-to-modify-teensy-core-files/7425/16

This repo is meant to be taken by platformio to replace the core libs used in default Teensy to allow for Xinput

Followed the architecture and implementation of: 
https://github.com/spinorkit/pio-arduinoteensy/tree/main

Replaced the core lib with the most up to date teensy libs: 
https://github.com/PaulStoffregen/cores/tree/master

MODIFIED FROM ORIGINAL: deleted the teensy3 folder to make things lighter and avoid conflicts

Replaced certain files within teensy4 subfolder with files found from this repo: 
https://github.com/dmadison/ArduinoXInput_Teensy/tree/master

MODIFIED FROM ORIGINAL: Swapped locations of USB_SERIAL and USB_XINPUT within usb_desc.h to allow USB_XINPUT flag to activate
