# Smart-Glove-for-Speech-and-Hearing-Impaired-People

## INTRODUCTION: 
- Sign language is the method of communication used by speech and hearing impaired people to communicate to each other. However, normal people find it difficult to understand sign language and this creates a communication barrier.  
- Smart Glove is designed for speech and hearing impaired people that converts Sign Language to text, thereby reducing communication barrier. It also monitors the pulse rate. 

## Block Diagram:

![Block diagram](https://user-images.githubusercontent.com/69421390/235312949-d09cc846-2960-46ac-9578-19d365638c15.jpg)

The hand glove is equipped with flex sensors, a pulse sensor and an accelerometer. The Arduino NANO receives the analog output from the accelerometer, flex sensors and pulse sensor. Inbuilt ADC in Arduino converts those analog signals into digital signals.  For a specific hand gesture, a particular set of instructions are written, which is then processed, and an output is generated in digital form. This generated output is then displayed on the serial monitor of the Arduino IDE. 

## Hardware Requirement:  
- Arduino NANO 
- Flex Sensors 
- Accelerometer ADXL335 
- Resistors 
- Pulse Sensor 
- Power Supply 
- Connector Cables 

## Software Requirement:  
- Arduino IDE 

## Circuit Diagram:
![Circuit diagram](https://user-images.githubusercontent.com/69421390/235313250-4bd96720-4e19-4587-b640-a378a79fd3c7.png)

## Result:

<src="https://user-images.githubusercontent.com/69421390/235313322-4812c710-679b-4f8a-bf37-e033ab8c2086.png">
![Hand Gesture 2](https://user-images.githubusercontent.com/69421390/235313330-3688971f-07f6-42ad-8997-e734361ae27c.png)
![Hand Gesture 3](https://user-images.githubusercontent.com/69421390/235313337-5cc74601-75f1-4c7c-a47d-4fdd85b1526f.png)
![Monitoring Pulse Rate](https://user-images.githubusercontent.com/69421390/235313343-76f86d22-2757-4fd1-a3be-342d1a8ad4f2.png)

![Monitoring Pulse Rate](https://user-images.githubusercontent.com/69421390/235313295-f6fddb3b-c4e7-4edc-a907-8d64f59046bf.png)
