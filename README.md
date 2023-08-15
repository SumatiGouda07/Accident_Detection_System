# Accident_Detection_System

An accident detection  is a system designed to detect accidents on roads and highways and notify emergency services to reach the accident site quickly. The system uses various sensors and GPS to identify the occurrence of an accident. The system's algorithms analyze the data from these sensors to determine location of the the accident. Once an accident is detected, the system automatically sends a signal to the emergency services,along with the location details, to enable them to reach the accident site promptly.

### INTRODUCTION 
In day to day life in we find the Road Accident because of usage of mobile phones while travelling, aggressive driving,improper zebra crossing line, overtaking in wrong manner,starting driving with improper instructions, avoiding safety ugears (helmet, seat belt).Thus the objective of this project is to avoid accident in drunk and drive situation and also to detect the accident spot so that the immediate medication for the victim will be given at earliest time as possible. The vehicle unit consist of sensors to detect the accident location and send the information to the
authorised person with the help of GPS& GSM.


### METHODOLOGY

#### Components Required
  * Arduino UNO
  * Alcohol sensor
  * Vibration sensor
  * SIM808 module
  * LCD display 16x2

#### Components Descriptionsl

  * #### Arduino
It is the main controller in the vehicle unit. The Arduino Uno is microcontroller board based on ATmega328. It is a 8- bit RISC processor with Harvard architecture. This board includes 14 digital I/O pins, a power jack, 6 analogue I/O pins, ceramic resonator-A16 MHz, a USB connection, an RST(reset) button, and an ICSP header. All these can support the microcontroller for operation by connecting this board to the computer. The power supply of this board can be done with the help of an AC to DC adapter, a USB cable, otherwise a battery.

  * #### Vibration sensor
   
Vibration sensor is required to find whether the machine or equipment is maintaining the normal vibration or not by comparing the continuous value with the threshold in the controller. In this we used an SW-420 vibration module, which works on voltage of 3.3V to the 5V. The sensor has a LM393-IC it is used as comparator to detect the vibration over a threshold point and provide digital data, Logic Low or Logic High, 0 or 1. During normal operation, the sensor provides Logic Low and when the vibration is detected, the sensor provides Logic High.
  
  * #### Alcohol sensor
MQ2 is used as a gas / smoke sensor. MQ2 Gas sensor works on 5V DC and draws around 800mW. It can detect LPG, Smoke, Alcohol, Propane, Hydrogen, Methane and Carbon Monoxide concentrations anywhere from 200 to 10000ppm. To calibrate the gas sensor, we need to hold the gas sensor near smoke/gas to detect the RED LED by turning
the potentiometer. Turn the screw clockwise to increase sensitivity or anticlockwise to decrease sensitivity. The comparator on the module continuously checks if the analogue pin (A0) has hit the threshold value set by potentiometer. When it crosses the threshold, the digital pin (D0) will go HIGH and signal LED turns on.

  * #### SIM808 module
SIM808 module is a complete Quad-Band GSM/GPRS module which combines GPS technology for satellite navigation. It supports up-to 1900MHz Quad-Band. With this module, we can send and receive SMS, terrace location. SIM808 module functions as GSM communicator and GPS receiver.

 * #### LCD Display
The LCD panel used in this block interfaced with micro-controller through output port. This is a 16 character × 2Line LCD module, capable of display numbers, characters, and graphics.

#### WORKING

This particular module is responsible for the avoidance of the accidents and also to send the accident location details to the registered user and police and also to the nearby hospital. Here the vibration sensor plays an important role in detecting the accidents whenever vehicle starts and moves it produces some vibration and when that vibration continuously monitored and compared with the threshold values of the sensor and whenever there is accident occurs the sudden increase in the vibration of the vehicle is considered as accident and then that location will be sent to the authorities with the help of GPS and GSM. An alert alarm will be given so that nearby people can help the victim from losing his/her life. Here we can also avoid the accident from happening in drunk and drive situation with the help of alcohol sensor whenever alcohol is sensed by the sensor then  n a message will be sent to the family member of driver along with the location details.

### CONCLUSION
This project helps in detecting the accident location and send alert signal to the nearby police station and also to the hospital so that the rescue unit will arrive as early as possible so that the life of the victim will be saved. Here our project has successfully detected the accident location and also avoided the drunk and drive case by sending the alert signal to the concerned one. 

