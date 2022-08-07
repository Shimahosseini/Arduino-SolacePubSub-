# Arduino-SolacePubSub-


In this project an automation code run to send data to the Solace pubsub+ and recive data from it.
To do that,the ESP32 devkit was chosen, and the functionality of CNC behavior was defined on it.
Two push buttons are used as the start and stop inputs.
Also, two light-emitting diodes (LED) (green and yellow) and one LCD (Liquid Crystal Display) are connected to the ESP32 devkit.
The green LED states that the machine is ready to work and the yellow LED shows that the CNC machine is working.
This script can connect to Solace PubSub+ broker and stream new states of these automation processes to it.
