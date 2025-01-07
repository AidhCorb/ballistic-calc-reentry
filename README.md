# ballistic-calc-reentry
A calculation of atmospheric reentry parameters based on required maneuver time and altitude profile.

This project was an attempt at gleaming useful parameters for designing capsule shape geometry and dimensions based on reentry parameters. 
The idea was to input the time the maneuver would need to occur, as well as the trajectory through Neptune's atmosphere the craft would
take, which could be used to decelerate the craft from its high incident speed upon arrival at Neptune from its interplanetary transfer
trajectory. This arrest would be a high G maneuver, requiring a capsule designed specifically for it. Thus, this code was designed to
calculate the ballistic coefficient and lift to drag ratio that the body would have to produce, in order to design a craft that performs
as such.
