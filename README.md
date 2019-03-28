# Raspberry-Pi-SmartCar
A smart car controlled by Raspberry Pi, can recognize images through Tensorflow
The car is controlled by Raspberry Pi 3B, with a capability of recognizing images captured through a camera. 

1. Movement is controlled by L298N modules
2. Elevation of the Raspberry Pi camera is controlled by 28BYJ-48 stepper motor and ULN2003APG module.
3. Image recognition is implemented through Inception-v3 module by Google Inc.
4. Results are displayed through a web page by RPI Cam web interface. Simultaneously, results are broadcasted through a speaker and Espeak    module
5. Commands are received by keystrokes through tornado module.
