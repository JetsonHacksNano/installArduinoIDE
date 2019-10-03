# installArduinoIDE
Install the Arduino IDE on the NVIDIA Jetson Developer Kit.

Consider donating to Arduino development at: https://www.arduino.cc/

As of this writing (October 2019) the Arduino IDE in the Ubuntu ARM 64 repository does not support the Jetson. This script downloads a version which supports the Jetson and installs it. To run the script:

$ ./installArduinoIDE.sh

<h3>Notes</h3>

Initial Release October, 2019
* L4T 32.2.1 / JetPack 4.2.2
* Installs Arduino IDE 1.8.10
* Tested on Jetson Nano
