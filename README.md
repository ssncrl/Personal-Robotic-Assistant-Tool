# PRAT
Project Summary:
A low-cost robotic assistant arm designed to help people perform small physical tasks by controlling it with their voice (pressing buttons, flipping switches, moving objects, grabbing objects). Built with Arduino, Python, ML, SpeechRecognition and Computer Vision


## Microcontroller (Arduino Side)

Software: Arduino IDE

Libraries Installed:

ArduinoJson — for handling JSON data exchange

SSD1306Ascii — for displaying text on OLED screens

IRremote — for infrared signal control

## Computer / Python Side (Windows)

Language: Python

Packages Installed:

pyserial — for serial communication between the computer and Arduino

speechrecognition — for voice command processing

opencv-python — for computer vision and object detection

pyaudio — for accessing the microphone input

These packages enable speech-controlled operation and visual object detection for the robot arm.

Features:
- multi-joint robotic arm
- voice-controlled routines

  
Expected Outcome: 

"Hey bot, grab the pencil."

Robot sees the object, plans the motion, picks it up, and hands it over

