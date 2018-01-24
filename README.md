# The Gender Bender

* 7 track probabilistic drum trigger generator
* Stand alone version (powered by USB) and eurorack module
* Simultaneous midi in/out, midi usb and modular trigger outputs
* Requires a clock signal to start/stop the sequence from either a voltage clock, midi or usb midi  input.
* 5 parameters per track density, division, fill, velocity and duration
* Independant LFOs per parameter per track/ instrument gives a total of 35 internal LFOs
* Each LFO has 5 parameters wave, division, amplitude, offset and PWM.
* Midiout x 2 (both midi connector and midiusb) with an additional 35 independant LFOs gives a total of 70
* 2 assignable CV INs for any parameter
* SD card for saving and loading patterns in text format
* Joystick for morphing between 9 different sequences per track
* Global parameters like division, density, fill, velocity and individual mutes per track for live performance
* Sequence edit mode
* Midi configuration per track with parameters like midi channel #, transpose multiplier, multiplication, division and midi note (cc messages modulated by LFO to produce notes)
* It is posible to save the current state of all the parameters into a snapshot on the SD card loading them on the fly during performance.
* Compatible with both Banana & minijack
* 28HP

# Videos

* [Demo with USB midi](https://www.youtube.com/watch?v=14ep21vwbiA)
* [Demo with eurorack](https://www.youtube.com/watch?v=5kgbRU3wxxo)

# Some details...

![the-gender-bender](https://user-images.githubusercontent.com/6823868/29998083-3386c7a6-9022-11e7-9b96-6b8f59b2f1cc.jpg)

- [Mouser project](https://www.mouser.es/ProjectManager/ProjectDetail.aspx?State=EDIT&ProjectGUID=648036c1-8d6a-4717-aa2b-a728f60b2be2)

Loosely based on the Mutable Instruments GRIDS (and Anushri),  _The Gender Bender__ can morph between 9 different patterns per track to create probabilistic rythms with different densities that are simultaneously sent via voltage trigger, midi and midi USB.



The name "The Gender Bender" refers to the character from ‘Futurama’ 


It incorporates the algorythmic permutation  (automatic breakbeat cutting) from Nicolas Collins's paper:
https://composerprogrammer.com/research/acmethodsforbbsci.pdf



Components:
* Teensy 3.2
* 5 encoders with push buttons
* 7 momentary push buttons
* Joystick (PS2 for instance), you need to remove the spring
* 1.3" OLED Display
* vertical Midi IN & OUT connectors
* vertical USB connector
* vertical MicroSD reader and micro SD card.

We recommend [TY TOOLS](http://neodd.com/tytools) for uploading the firmware

- [Mouser project](https://www.mouser.es/ProjectManager/ProjectDetail.aspx?State=EDIT&ProjectGUID=f296fdb6-94c8-4a3b-bbea-0cd3ca61aec2) Without minijacks.
