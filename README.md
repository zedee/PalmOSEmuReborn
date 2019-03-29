# PalmOSEmuReborn
Just playing resurrect Palm OS Emulator (former Copilot) to port it to x64 platform.

Known dependencies:

`libfltk`

If you're on Ubuntu/Debian, you can fetch this library doing the following:

`sudo apt install libfltk1.3-dev libfltk1.3-compat-headers`

Then try to compile by running:

`./configure --with-fltk=/usr/include/FL && make`
