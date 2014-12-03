Flight Gear Interface Custom Device
http://www.ni.com/example/31364/en/

================
####*This repository and any materials provided by NI therein are provided AS IS. NI DISCLAIMS ANY AND ALL LIABILITIES FOR AND MAKES NO WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR  PARTICULAR PURPOSE, OR NON-INFRINGEMENT OF INTELLECTUAL PROPERTY. NI shall have no liability for any direct, indirect, incidental, punitive, special, or consequential damages for your use of the repository or any materials contained therein.*
================

This custom device blasts data over UDP from the RT Target to a PC with flight gear on it.

In flight gear, setup the control to be from "external FDM" and UDP. Select a port.

In this custom device, set the IP address target to be the machine that is hosting flight gear, and the port to be the same as what you set in flight gear. Then map the inputs to the custom device with the outputs of your model:
-Airspeed
-Altitude
-Latitude
-Longitude
-Phi
-Psi
-Theta