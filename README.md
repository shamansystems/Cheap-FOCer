# Cheap-FOCer
BLDC Motor Controller based on the VESC 4.12 hardware



Advantages

Lower build and BOM cost

TO-220 FETs allow for big heat sink attachment for better thermal performance

SMD components no smaller than 0805 make hand assembly practical

Added ON/OFF capability to turn off control circuitry when controller is not in use. A simple mechanical switch will achieve this when connected to the “ON/OFF” 2-pin header.

Can fit in typical “350W” ebike enclosures

Can fit in Hammond 1590b enclosures



Disadvantages (that I know of)

Larger than original VESC. Cheap VESC is 45mm x 92mm

Higher profile with TO-220 package FETs

Additional assembly steps to beef up high-current traces. 2 layers of 1oz copper can’t handle the current flowing through during operation. Assembler will have to apply wire/solder wick/bus bar to the exposed Power, Ground, and Phase traces that you can see in the “bottom” image.
