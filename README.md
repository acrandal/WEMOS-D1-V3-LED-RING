# WEMOS D1 V3 LED RING

This is a quick design for a ESP8266 based WEMOS D1 mini v3 and a 24 pixel RGB LED (Neopixel) ring.

The goal of the project was actually for a larger undertaking with multiple outer rings, but this was sufficient for my needs.
It allows for the ESP8266 to be cleanly mounted along with the lights.
Ideally, this will be connected over wifi to a MQTT queue to control the light display.

It's designed to hold both of the devices in a low profile, well structured frame.
The two pins for the D1 mini mounting holes are correct for some of my boards, but others needed to have one post clipped off for a perfect fit.
Next steps could include a partially opaque acryllic cover to diffuse the lights and protect the contents.

The included CAD file is in FreeCAD format.

I printed my example with the included STL file on a Creality Ender 3 Pro.

In my case, the LED data line is in pin D4.
This is reflected in the included Arduino ino file.
The included Arduino code is just the Adafruit Neopixel example 'srandtest' with the pin and light quantities updated for this project.

----

TODO:

1. Raise edges of the 3D printing ring to allow a cover to be flush across the whole face.
2. Open larger gap on bottom for USB cable egress route.
3. Move D1 frame over to make cable routing straighter.
4. Widen wiring hole out of D1 frame for all 3 wires to more easily lie down.


Author: Aaron S. Crandall \<crandall@gonzaga.edu>
Copyright: 2021  
License: GPL v3.0
