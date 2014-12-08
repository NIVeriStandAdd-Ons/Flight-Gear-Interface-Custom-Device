## Flight Gear Interface Custom Device ##

**Flight Gear Interface Custom Device** blasts data over UDP from the NI VeriStand Target to any PC with Flight Gear 2.0 on it.

In flight gear, setup the control to be from "external FDM" and UDP. Select a port.

In this custom device, set the IP address target to be the machine that is hosting flight gear, and the port to be the same as what you set in flight gear. Then map the inputs to the custom device with the outputs of your model:
-Airspeed
-Altitude
-Latitude
-Longitude
-Phi
-Psi
-Theta

### LabVIEW Version ###

LabVIEW 2010

### Built Availability ###

This IP is built and available for NI VeriStand 2010 [here](http://www.ni.com/example/31364/en/) but will be taken down soon.

### Quality, Limitations ###

This IP was made in 2011 and has not been tested since. There are several known users of the IP in NI VeriStand 2011 with Flight Gear 2.0, but no updates since then. Proceed with caution.

### License ###

*This repository and any materials provided by NI therein are provided AS IS. NI DISCLAIMS ANY AND ALL LIABILITIES FOR AND MAKES NO WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR  PARTICULAR PURPOSE, OR NON-INFRINGEMENT OF INTELLECTUAL PROPERTY. NI shall have no liability for any direct, indirect, incidental, punitive, special, or consequential damages for your use of the repository or any materials contained therein.*

