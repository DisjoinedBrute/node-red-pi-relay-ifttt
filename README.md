# node-red-pi-relay-ifttt
## Node red relay code for 4 channel relay (or GPIO pins) and iftttt
### Uses dataplicity wormhole and ifttt web request
------------------------------------------------------------------------------------------------------------------------------------------
## Setup 
Update to latest raspbian  ```sudo apt-get update && sudo apt-get upgrade``` and run node-js with ```sudo node-js```\
Setup dataplicity from [here](https://www.dataplicity.com/)\
Once setup enable wormhole and copy the address.\
Go to [IFTTT](https://ifttt.com)\
Connect web request to your account and edit the url to 'your_dataplicity_server/incoming1 (incoming1 can be replaced with anything)\
On node-js edit the incoming https request to ```/incoming1```
Change the gpio output to the pins connected\
### The node-js is connected to IFTTT service 
-------------------------------------------------------------------------------------------------------------------------------------------
## Usage example:
Using Google assistant to toggle a relay:\
Connect Google Assistant to your account in IFTTT.\
Verify your device and create an applet\
In the 'IF this' part setup the command for the Assistant.in 'Then that' part use web request and set it ip up the steps given above.

# Testing
Say the command set up on Google Assistant and it will trigger a web request to the dataplicity link.The pi is waiting for the webreqest
at a specific sublink setup up. To use more triggers simply change the web request to /incoming2 etc.

-------------------------------------------------------------------------------------------------------------------------------------------



