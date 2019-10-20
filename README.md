# cautious-parakeet

## Goals

### Install Bluetooth module.
Have to connect bluetooth module to arduino and make it work.(Testing with a mobile or laptop)

### Install relay.
Have to install relay between RGB lights and Arduino.

### Create APP.
App should send a 1 byte of data which contains the data of each LED.

 0 0  -  Intensity Data
 0 0  -  Red Data
 0 0  -  Green Data
 0 0  -  Blue Data        

For RGB 
00 - Off
11 - On

For Intensity
00, 01, 10, 11 -  Intensity Level 0-3.

will send what you want to glow from the app with the above 1 Byte of data to arduino.

Arduino will encode that 1 Byte of data and pass instructions to relay.
