# USB Cable Tester
This is a simple tester for USB cables with USB A and Micro USB B.

## Usage

### Cable test
Connect a cable to both ends of the tester. All four LEDs should light up.

If a LED isn't lighting up the corresponding wire might be broken or not connected.
Some cables come without the wires for data transmitting. These type of cables is only suiteable for slow charging a device and can be easily detected if the LEDs for D+ and D- are not connected.

### Battery test
To check if the battery is working disconnect any connected cable.
Press the button. All LEDs should light up.

### Testpads
You can also use the testpads for checking the data lines of your cable.
Connect a probe of your multimeter to TP1 and then check every other testpad for a connection.

## Build
The build is straightforward but contains SMD components with a small footprint (0603).
See the [bom.md](bom.md) for details.

The board and schematics were created with [https://kicad-pcb.org/](KiCad) and can be found in the `board/` directory.

I used OSHPark for manufactoring, you can order this version directly at //TODO add OSHPark link 

Have fun. 
