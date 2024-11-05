![UCSD ECE Logo](./UCSDLogo-JSOE-ElectricalandComputerEngineering-BlueGold-Web.jpg)

<h1 style="text-align:center;"><b>Improving Pedestrian Safety at Intersections</b></h1>
    
<h3 style="text-align:center;"> Shlok Damani, Ryan Ho, Aarav Masrani, Dibyesh Sahoo</h3>

<h3 style="text-align:center;"> Fall 2024</h3>

## Problem
Intersections are often difficult to navigate through. Traffic both vehicular and pedestrian can cause risks to safety of the pedestrians. 

## Proposed Solution

The proposed solution for our **Pedestrian Safety System** aims to enhance road safety by automatically detecting pedestrians and alerting drivers through visible signals. The system uses two ESP32 Cam modules positioned strategically: one monitors pedestrian crossings, and the other scans the street for jaywalking. When a pedestrian is detected, a warning light on an RGB LED matrix is triggered, alerting oncoming traffic.

To ensure reliable, wireless communication between the modules, we integrated LoRa technology. The setup is solar-powered, utilizing a TP4056 charging module to maintain the battery, and regulated by an MCP1700 LDO to consistently supply the ESP32 with 3.3V. This design not only addresses pedestrian safety but does so sustainably by leveraging solar power and low-power communication for continuous operation in diverse environments.


## Hypothesis

Our solar-powered smart pedestrian crossing system will automatically detect incoming pedestrians whether or not they are on the crosswalk or not. 

**Measurement Method**: We will go to pedestrian crossing, and in order to test our system, we will cross the road from different locations and at different angles, both inside the crosswalk and outside the crosswalk. Regardless of the angle and location, our LED’s should start flashing to indicate there is someone crossing. 

## Milestones
1. Design PCB schematic (Monday- Week 5)
2. Design PCB board (Thursday- Week 5)
3. Be able to take pictures using the ESP-32S3 Board (Saturday – Week 5)
4. Have basic object detection model (Sunday - Week 6)
5. Assembly of PCB including soldering of external components (Friday- Week 7)
6. Use the model to detect people using ESP-32S3 Board (Sunday - Week 7)
7. Be able to charge battery using Solar Panel, and connect that to our ESP32 Board (Monday - Week 8)
8. Creating custom software SPI pins for the LoRa transceiver, and interfacing it with the camera and RGB LEDS, and other ESP32 boards(Monday- Week 8)


## Video Ideas

[Poster Link](https://docs.google.com/presentation/d/1piVCpWneqZ5gmzYCBuGzzY3xZIutdS-CmckrON2Q2YI/edit?usp=sharing)
   

