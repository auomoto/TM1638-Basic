Version 4 was done at OSHPark but came with one problem. Pin 14 on the
ATtiny841 (GND) was not connected to the ground plane even though it
looked like it should be. Pin 14 is correctly connected to the ground
side of the decoupling capacitor and the spider connections on the ground
plane side of the capacitor through hole are there, but it doesn't actually
connect.

Solution: run a jumper wire on the top of the board from the capacitor to
the nearby header pin that's at ground. This works.
