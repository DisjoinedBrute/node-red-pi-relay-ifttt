# Raspberry Pi iot project based on IFTTT and NODE
## Code for 4 channel relay (or GPIO pins) and ifttt
### Uses dataplicity wormhole and ifttt web request
------------------------------------------------------------------------------------------------------------------------------------------
## Setup 
Update to latest raspbian  ```sudo apt-get update && sudo apt-get upgrade``` and install from [here](https://nodered.org/docs/hardware/raspberrypi)\
Setup dataplicity from [here](https://www.dataplicity.com/)\
Once setup enable wormhole and copy the address.\
Go to [IFTTT](https://ifttt.com)\
Connect web request to your account and edit the url to <your_dataplicity_server>/incoming1 (incoming1 can be replaced with anything)\
Run node-red by typing ```node-red```\
Import the node-js code to node-red. This can be done by using the import tab in menu. Select import via clipboard and paste the code\
### Library can be imported directly now.
Deploy the code.Change the gpio pins according to the wiring done Edit the incoming https request to ```/incoming1```(or whatever you used in IFTTT). 
### For UI control:
You will have to install the dashboard node for this functionality. More details are [here](https://github.com/node-red/node-red-dashboard).It can be accesed on the pi's ip/ui
### Node-red is now connected to IFTTT service 
-------------------------------------------------------------------------------------------------------------------------------------------
## Usage example:
Using Google assistant to toggle a relay:\
Connect Google Assistant to your account in IFTTT.\
Verify your device and create an applet\
In the 'IF this' part setup the command for the Assistant. In 'Then that' part use web request and set it ip up using the steps given above.

# Testing
Say the command set up on Google Assistant and it will trigger a web request to the dataplicity link.The pi is waiting for the webrequest
at a specific sublink setup up. To use more triggers simply change the web request to /incoming2 etc.

------------------------------------------------------------------------------------------------------------------------------------------

