Freetronics ProtoShield Pro
=============================
Copyright 2010 Freetronics Pty Ltd  
Freetronics site:  <www.freetronics.com>  
Freetronics email: <info@freetronics.com>  

A general-purpose prototyping shield for the Arduino Duemilanove,
TwentyTen, and other compatible boards based on the same header format.

This design is intended to maximise prototyping area by extending the
plain pads right to the ends of the board, which also makes it easier
to fit horizontal PCB-mount sockets that need to overlap the edge.

Note that this design uses 0603 surface-mount parts for the supporting
components such as the LEDs, decoupling capacitors and buttons. If you
want a board that uses entirely through-hole parts please look at the
"ProtoShield Basic" project, also from Freetronics.

Features:

 * Reset button wired through to Arduino reset pin.
 * Additional momentary button (output biased low by 10k resistor and
   pulled HIGH by the button).
 * Red and green general-purpose SMT LEDs with current-limiting
   resistors (drive HIGH to illuminate).
 * Blue "power on" LED with current-limiting resistor.
 * Large GND and 5V power rails alongside the prototyping area.
 * 2 x 100nF bypass/smoothing capacitors on supply rails.
 * Overlay guide where you need it: both top and bottom.

More information is available on our product page at:

  http://www.freetronics.com/products/protoshield

The "docs" folder within this repository includes a handy copy of the
schematic in PDF format and image(s) of the pcb.


INSTALLATION
------------
The design is saved as an EAGLE project. EAGLE PCB design software is
available from www.cadsoftusa.com free for non-commercial use. To use
this project download it and place the directory containing these files
into the "eagle" directory on your computer. Then open EAGLE and
navigate to Projects -> eagle -> ProtoShieldPro.


DISTRIBUTION
------------
The specific terms of distribution of this project are governed by the
license referenced below.


LICENSE
-------
Licensed under the TAPR Open Hardware License (www.tapr.org/OHL).
The "license" folder within this repository also contains a copy of
this license in plain text format.
