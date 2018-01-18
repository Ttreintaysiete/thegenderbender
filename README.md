# The Gender Bender

* 7 track probabilistic drum trigger generator
* stand alone (powered by USB) and eurorack
* simultaneous midi in/out, midi usb and modular trigger outputs
* 5 parameters per track density, division, fill, velocity and duration
* independant LFOs per parameter per instrument for a total of 35 internal LFOs
* each LFO has 5 parameters wave, division, amplitude, offset and PWM.
* midiout (both midi connector and midiusb) with another 35 independant LFOs for a total of 70
* 2 assignable CV INs to any parameter
* SD card for saving and loading patterns in text format
* joystick to morph between 9 different sequences per track
* global parameters like division, density, fill, velocity and individual mutes per track for live performance
* sequence edit mode
* midi configuration per track with parameters like midi channel #, traspose multiplier, multiplication, division and midi note (cc messages modulated by LFO to produce notes)
* compatible with Banana & minijack
* 28HP

# Videos

* [Demo with USB midi](https://www.youtube.com/watch?v=14ep21vwbiA)
* [Demo with eurorack](https://www.youtube.com/watch?v=5kgbRU3wxxo)

# Some details...

![the-gender-bender](https://user-images.githubusercontent.com/6823868/29998083-3386c7a6-9022-11e7-9b96-6b8f59b2f1cc.jpg)

- [Mouser project](https://www.mouser.es/ProjectManager/ProjectDetail.aspx?State=EDIT&ProjectGUID=648036c1-8d6a-4717-aa2b-a728f60b2be2)

Loosely based in the Mutable Instruments GRIDS (and Anushri), the __Gender Bender__ can morphs between 9 different patterns per track to create probabilistic rythms with different densities that are simultaneously sent via voltage trigger, midi y midi USB.

The name __Gender Bender__ refers to the capability of mixing or __bend__ different drums rythms and styles in the same pattern, for instance you can choose the BD from techno, HH from drum&bass, TOMS from samba, etc... and an infamous [Mexican Bender robot](https://en.wikipedia.org/wiki/Bender_(Futurama)).

It has the posibility to save the current state of all the parameters into a snapshot in the SD and to load it on the fly for performance.

It incorporates the permutation algorythm (automatic breakbeat
cutting) from Nicolas Collins's paper:
https://composerprogrammer.com/research/acmethodsforbbsci.pdf

It requires a __clock signal__ from either its clock input, midi or usb midi to start/stop the sequence.

Components:
* Teensy 3.2
* 5 encoders with push button
* 7 momentary push buttons
* Joystick (PS2 for instance), you need to remove the spring
* 1.3" OLED Display
* vertical Midi IN & OUT connectors
* vertical USB connector
* vertical MicroSD reader and micro SD card.

We recommend [TY TOOLS](http://neodd.com/tytools) for upload the firmware
