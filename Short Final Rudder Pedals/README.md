
# Short Final Rudder Pedals

Open Source PC flight sim rudder pedals. Intended to be robust, easily usable and customzable.

All sensing is done through hall effect sensors, so no wear.

All motion is through ball bearings or linear rails. The pedals are joined by GT2 belts, which actuate a center pulley designed to rotate 180° at full travel, thus giving maximum resolution to the pedals.

The electronics are simple, just an Arduino Pro Micro clone. I got one with a USB C port instead of USB Micro because it's more robust. I think a Teensy would do well here too, but can't find one with a USB C port. The toe brakes have a FPC (Flexible Printed Circuit) ribbon cable which works like wires with a cable chain, but is less bulky and fits in the channel of the extrusion.



## Roadmap

- Finish up GitHub page

- Actually build the first physical set...then optimize. My first part is on the printer currently.

- Add a nice assembly manual.


## FAQ

#### What printer should I use?
I print on a Voron 2.4 350 mm. I designed this to fit on a 350 mm². If you have this size printer, you should be fine. Sorry, it probably won't work on an Ender 3. The main pulley is larger than the print bed of an E3. If you absolutely can't get the parts printed, I might be convinced to print parts out for a nominal fee to cover cost and shipping, if I have time.

#### What filament should I use?
ABS or ASA. It's strong and durable. PLA is easy to print, but warps under continued stress. If you're one of those guys that prints Nylon or PEEK, you go brotha! (Also, send me a set of parts...for science!)

#### What are the print parameters?
I use the standard Voron print settings for almost everything. That amounts to:
- 4 perimeters
- 5 top and bottom shells
- ~40% infill (Gyroid or Cubic preferred)
- 0.2 mm layer height
- 0.4 mm nozzle (however, you could likely use a 0.6 mm nozzle and save some time.)


## Bill of Materials
Here will be the bill of materials when I finally have that all calculated.
