This porject uses a Raspberry Pi PICO Microcontroller with sensors that relay their inputs and outputs through a network setup with a Raspberry Pi Zero W. The inputs sent from the PICO travel through the network and logs the data onto the M5Cardputer Microcontroller. Additionally, the M5Cardputer can turn sensors from the PICO on and off remotely through the network.

Features of the M5Cardputer are done through SSH. The Zero W is the Server. The PICO is the sensor unit.

Moreover, for the PICO to begin its operations, a user of the M5Cardputer must login to access the network and thus deliver commands to the PICO and receive data from the pico.

Encryption of connection between the M5, Server, and the PICO are applied. Vulnerability research is still nascent. More to follow.