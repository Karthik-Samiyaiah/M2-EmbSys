# AUTOMATIC RAIN SENSING CAR WIPER


## INTRODUCTION
-- Driver safety issues are of great importance in today's automotive industry. Lack of visibility is often the cause of heavy rain accidents. In many cases, manual errors such as the driver not increasing the wiper speed can lead to an accident. Today's car wipers work on the principle of manual switching. In this article, we have proposed an automated wiper system with a rain sensor that detects rain and automatically starts and stops when it stops. The automatic wiper system with rain sensor is not only automatic but also intelligent


## PROPOSED SYSTEM
-- This is an automatic wiper system that turns on automatically when it rains and stops when it stops raining. We will use a servomotor, rain sensor Arduino, and LCD module to control the wiper system. Whenever it rains, the rain sensor detects the intensity of the rain and sends that information to the Arduino. The information collected by the rain sensor is processed by Arduino and the processed information is sent to the servo motor to perform the desired action. The rain sensor consists of digital-to-analog output pins that calculate the intensity of the rain. The information sent to the microcontroller controls the speed of the wiper and is based on the intensity of the rain. The LCD shows the intensity of precipitation. 


## SWOT ANALYSIS
**Strength**
-- Automatically turns on wipers in cars when it rains.

**Weakness**
-- In order to avoid false detection of rain, it requires rain sensors to take decision after few minutes.

**Opportunity**
-- used in Autonomous vechicles.

**Threats**
-- TBD

# 4W&#39;s and 1&#39;H

## Who:

**Drivers can use automatic rain sensing wipers in their cars.**

## What:

**Automatic Rain sensing car wipers is mainly concerned to help drivers.**

## When:

**Automatic rain sensing wipers are in useful during rainfall.**

## Where:

**User can fix this wiper in car windshield.**

## How:

**Implementation is done using Arduino,Rain sensor and servo motors.**

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

## SOFTWARE REQUIREMENTS
* Arduino compiler
* Proteus software

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
 
## SENSOR
## Rain Sensor
-- A rain sensor is a device used to detect raindrops. These are electrically separated and can be used as printed circuit boards. The function of the rain sensor can be properly compared with the function of the switch. 

## ACTUATOR
## Servo Motor
-- A servomotor (or servo motor) is a rotary actuator or linear actuator that allows for precise control of angular or linear position, velocity and acceleration. It consists of a suitable motor coupled to a sensor for position feedback.

## ARDUINO
-- The Arduino Uno is also a microcontroller board supported the ATmega328.it's fourteen digital input/output pins six analog inputs, a sixteen megacycle oscillator, a USB association, an influence jack, associate degree ICSP header, and a push button.
