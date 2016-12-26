# Using LIFI to transfer data to be played on a Piezo buzzer

### Concept
Using LIFI to Transfer Audio Data and Playing it on A Buzzer. This can all be achieved using an Arduino. The purpose is to prove that LIFI can be used to transfer useful information in an efficient way. This information can be used to play music using a buzzer. Since only one Arduino is used, the receiver and the transmitter will be mimicked. It doesn't resemble a realistic transmitter and receiver because there will be no synchronization. Although this is the case, the code is written in a way that allows for this type of expansion and have a common period for serial transmission. 

### LIFI Transmission
To learn more about the transmission algorithm, read : 
At optimal conditions, I was able to achieve transfer rates of over 3000 bits/second using one LED. 
### Items Needed

* Arduino Uno
* LDR (photoresistor)
* 100 ohm resistor
* 200 ohm resistor
* LED
* Piezo buzzer

### Schematic
![Schematic](https://github.com/AkilaJay/LifiWithBuzzer/blob/master/Images/Sketch%202_bb.png?raw=true "Schematic of the project")
### Protocol

I used a very simple protocol with inband signaling to make the transfer. The packet information is illustrated in the image below. 

![Schematic](https://github.com/AkilaJay/LifiWithBuzzer/blob/master/Images/packet_info.PNG?raw=true " Data packet information")

### Video 

[![Click to view video](https://github.com/AkilaJay/LifiWithBuzzer/blob/master/Images/IMG_20161226_192706.jpg?raw=true)](https://www.youtube.com/watch?v=jUcepD56kts)

### License
MIT


