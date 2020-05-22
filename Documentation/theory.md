## THEORY

LED used in common household can itself very easily be used as binary system itself; Serving both, a luminiscent source as well as module in
data transfer. We exploit this property of LEDs to transfer data over distance. Also, eyes cannot detect a light flicker of frequency over 25 Hz, 
so it is safe say that it won't interfere with any of its primary usage.
Currently, circuit advancements and improvements are being done on PROTEUS PROFESSIONAL, for simulation purposes using single wire to communicate
between two Arduino UNOs.

**TRANSMITTER** part of circuit has following steps involved :
1) Arduino UNO for encoding arbitary data into binary format.
2) Implentation of Networking Protocols for efficient data transfer.
3) LED for transmission of data in medium.

[!image](arduino.PNG)

Currently, **RECEIVER** being simulated online, can directly detect variation in voltage. Steps involved in Reciever part are:
1) Conversion of analog signal to digital signal which is being fed to Arduino.
2) Converting received binary data to original data in microcontroller.
