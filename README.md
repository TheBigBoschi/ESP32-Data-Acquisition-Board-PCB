# ESP32-Data-Acquisition-Board-PCB
Custom PCB holding an ESP32, various sensor, a LoRa transmitter and the power management to run off a single lithium battery, charged by solar power.

To keep the development time short for this first revision I have made extensive use of various commercial modules, such as a TP4056 module, a few TPS63020 and a CN3791 to handle the power conversion. In the second revision they will be integrated directly on the board.

Particular care has been taken to properly decouple the ESP32 power supply, as a switching regulators are slow to react to the sudden bursts of energy required by the ESP32 transmitting data, and various capacitor have been added to give time to the regulator to respond.


![alt text](<Render Front.png>)

![alt text](<Render Rear.png>)