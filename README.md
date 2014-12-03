E11
===

##Contact
Sherman Lam
slam@g.hmc.edu / shermanator94@yahoo.com
(626)383-1787

##Overview
This repository is used for storing any data for HMC's E11 course. It is primarily used for keeping track of the the beacon boards used for the competition playing field. The beacons are all designed using Eagle. Included in this repository is a library for custom components.

##Beacon Boards 

###V2

Second generation beacon boards and features uniformity between all types of beacons. All boards have the same code and hardware. This board was used in the 2014 Fall E11 course.

####Features
- All boards are capable of being bumped or flashed to. 
- 1 switch to select between bonus beacon mode vs normal mode
- 1 switch to select between flash vs bump modes
- SPI broken out
- All LEDs on transistor circuits

####Known Issues
- Gold-Code-flashing LEDs are spaced too far apart. Deadband when too close
- Push buttons work but are hard to push and can only be pushed from certain angles
- Current limiting resistors have debatable values. Adjust as needed.
- Gold code flashing LEDs need a current limiting resister per LED. Can't share
- LEDs currently powered off VDD (whatever comes in). Change to regulated 5V
- Board is slightly too long and jams on the playing field.


###V3

Third generation board that uses the 2nd generation board's general layout but fixes the known issues. This board has not been produced.

####Features
- Uses the omron tactile switches (B3F-4050).
- Additional switch to select between starting color.

####Known Issues / TODO
- Change switch for starting color to 3 pos? (green, white, unclaimed).