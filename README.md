# RooPad-ADJ
Fixed QMK Code and Scans of the circuit board and housing plates of Skippy's Custom PCs' RooPad (Consider this an Archival Backup aswell)

The code found on QMK Config had made the numpad act in a weird way, where the leds did not work and the certain rows and columns were either off (pressing 1, displayed 2 on screen) or not at all (enter, + - - did not work at all!).

I fixed the code found on the QMK Config website, this was the following errors that I was getting:  
First column worked well.
Second and Third column were off by a column (e.g. pressing number 1 equaled to 2 popping up on screen)
Fourth and Fifth Column did not work.
First Row did not work (Num Lock, /, *, -).
LEDs did not work at all.

I fixed the code by implementing the correct matrix col and row pin numbers and the led pin number.


The following below is just information found on the sale page of this Numpad on Skippy's Custom PCs website:


<h3>  RooPad™ Carbon Mechanical Numpad Assembled </h3>

Want a unique quality mechanical keyboard but don't want to assemble it yourself? Then get us to do it! We can customise the CarbonPad Skeleton and RooPad to your selections and assemble it with switches installed ready for keycaps.

Genuine 3K 1.5mm Carbon Fibre top and bottom panel for use with PCBs like the RooPad™. Comes with 4x 10mm anodised aluminium stand-offs. Has pre drilled 4mm mounting holes for feet. As with all our products it comes with a 5 year replacement warranty covering you for defects during normal use. 

We have a purchasable extended warranty with accidental coverage for this product. Select the option below, and your purchase will be protected from drops, spills, accidents, everything but theft, lost items and misuse/abuse for 3 years. See the full details of our warranty program below.****

A hot swappable mechanical numpad PCB with RGB and USB type C. No soldering required!

Now everyone can create a custom, fully programmable numpad without any tools or experience!  

    Hot swappable for MX switches.
    Standard ANSI layout only.
    Fully programmable with QMK and VIA.
    RGB SMD InSwitch North-facing LEDs 
    Supports PCB mount and Screw in stabs.
    1m braided USB C to USB A cable included
    Has all 21 switches of your choice pre-installed 

Fully programmable using QMK.

QMK Firmware Badge

 

Red and black PCBs have white logo and print, white PCB has black logo and print.

 
