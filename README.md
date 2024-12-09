Vortex Parts
============

A step file containing the 3D printable parts for the Vortex swept volume
display. It's designed around some components I had to hand, and probably
wouldn't be the optimal design if you're starting from scratch. I hope it
is at least a useful reference.

Additional Components
---------------------
* The frame holds two P1.875 128x64 LED panels. FrameA and FrameB replace the
rubber mounts on the original panels
* Two 6mm x 225mm carbon fibre rods hold the panels rigidly to the core
* The core holds a Raspberry Pi 4, a Hub75 interface (similar to [this](https://github.com/hzeller/rpi-rgb-led-matrix/tree/master/adapter))
and a photointerrupter for synchronisation
* The top bearing is a hefty 6015. It's large enough for a Pi to fit through
* The bottom bearing is a 6804
* The slip ring is from a car alternator - parts ASL9013 and ABH6004S
* Power supply is a Mean Well LRS-100-12
* Motor is a YM2776

There are two options for the control dial. The fancy version uses a
Raspberry Pi Pico W, an accelerometer, another a rotary encoder and a
Waveshare 1.28" round touch screen. The accelerometer is to help with dynamic
balancing (if you build one of these you'll be spending a lot of time
balancing it). The alt version is just a motor speed controller and a knob.

The casing is designed to hold a truncated 300mm sphere over the spinning
parts. I used a post top lamp, cut to size. I've included the jig I used to
hold a Dremel in the existing opening and make a neat cut.

When you're peering into your rickety spinning contraption, make sure you're
wearing eye protection.
