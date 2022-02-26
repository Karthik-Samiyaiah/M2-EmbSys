# AUTOMATIC RAIN SENSING CAR WIPER


## INTRODUCTION
-- Driver safety issues are of great importance in today's automotive industry. Lack of visibility is often the cause of heavy rain accidents. In many cases, manual errors such as the driver not increasing the wiper speed can lead to an accident. Today's car wipers work on the principle of manual switching. In this article, we have proposed an automated wiper system with a rain sensor that detects rain and automatically starts and stops when it stops. The automatic wiper system with rain sensor is not only automatic but also intelligent


## PROPOSED SYSTEM
-- This is an automatic wiper system that turns on automatically when it rains and stops when it stops raining. We will use a servomotor, rain sensor Arduino, and LCD module to control the wiper system. Whenever it rains, the rain sensor detects the intensity of the rain and sends that information to the Arduino. The information collected by the rain sensor is processed by Arduino and the processed information is sent to the servo motor to perform the desired action. The rain sensor consists of digital-to-analog output pins that calculate the intensity of the rain. The information sent to the microcontroller controls the speed of the wiper and is based on the intensity of the rain. The LCD shows the intensity of precipitation. 


## BLOCK DIAGRAM
--   ![wiper](https://user-images.githubusercontent.com/99133249/155835355-eb0a6445-fae6-4e4d-8a89-654f7c0a57eb.jpg)


## HARDWARE REQUIREMENTS
* Atmega Microcontroller
* Rain Drop Sensor               
* Servo Motor                    
* Crystal Oscillator             
* Resistors                        
* Capacitors                                      
* Transistors                      
* Diodes
* LED
* Transformer/Adapter
* Push Buttons
* Switch
* IC

## High Level Requirements:
-- ID | Description |
----- | ------------|
HLR1| Wiper starts automatically when it rains | 
HLR2| Wiper speed can be changed | 
HLR3| Wiper stops automatically when the rain stops| 

## Low Level Requirements:
-- ID | Description | 
----- | ------------|
LLR1| User can see the wiper status in lcd display |
 
