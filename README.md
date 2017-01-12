# baudrate
Used for detecting the baud rate of a serial port

usage:

eve@eve:~$ sudo ./baudrate.py -p /dev/ttyUSB0

Starting baudrate detection on /dev/ttyUSB0, turn on your serial device now.
Press Ctl+C to quit.


@@@@@@@@@@@@@@@@@@@@@ Baudrate: 115200 @@@@@@@@@@@@@@@@@@@@@


We can change the baud rate to the next higher/lower baud rate by pressing the up/down arrow keys respectively

@@@@@@@@@@@@@@@@@@@@@ Baudrate: 115200 @@@@@@@@@@@@@@@@@@@@@


@@@@@@@@@@@@@@@@@@@@@ Baudrate: 57600 @@@@@@@@@@@@@@@@@@@@@    <--- Down arrow decreases baud rate


@@@@@@@@@@@@@@@@@@@@@ Baudrate: 115200 @@@@@@@@@@@@@@@@@@@@@    <--- Up arrow increases baud rate



Pressing Ctl+C we can stop the capture and save the settings to a minicom config file, in this case I just named it ‘9100em’:

Detected baudrate: 115200

Save minicom configuration as: 9100em
 
Configuration saved. Run minicom now [n/Y]? n

eve@eve:~$
