Revisiting some very old code to run a CNC machine.

Much has changed from when the original codebase was written back in the late 1990s.
Views on coding have changed considerably over the last 30 years or so. Hardware is much more capable and embedded processors such as the STM32, ESP32, and RP2350 compare very favourably in comparision to the old Intel 486/586 processors.

[grblHAL](https://github.com/grblHAL) demonstrates the efficiency of running the core motion planning and execution on embedded processors quite nicely. Unfortunately, most of the GUI frontends are geared towards 3D printers, have too many bells & whistles, and have the feel of a games console. None support tool offsets, and rotary axis support seems to be an afterthought.
