![UCSD ECE Logo](./Images/UCSDLogo-JSOE-ElectricalandComputerEngineering-BlueGold-Web.jpg)

<h1 style="text-align:center;"><b>Improving Pedestrian Safety at Intersections</b></h1>
    
<h3 style="text-align:center;"> Shlok Damani, Ryan Ho, Aarav Masrani, Dibyesh Sahoo</h3>

<h3 style="text-align:center;"> Fall 2024</h3>

## [Our Team](https://rhoqan.github.io/final-project-team-10-website/Our_Team.html)

## Problem
Intersections are often difficult to navigate through. Traffic both vehicular and pedestrian can cause risks to safety of the pedestrians. 

## Proposed Solution

The proposed solution for our **Pedestrian Safety System** aims to enhance road safety by automatically detecting pedestrians and alerting drivers through visible signals. The system uses two ESP32 Cam modules positioned strategically: one monitors pedestrian crossings, and the other scans the street for jaywalking. When a pedestrian is detected, a warning light on an RGB LED matrix is triggered, alerting oncoming traffic.

To ensure reliable, wireless communication between the modules, we integrated LoRa technology. The setup is solar-powered, utilizing a TP4056 charging module to maintain the battery, and regulated by an MCP1700 LDO to consistently supply the ESP32 with 3.3V. This design not only addresses pedestrian safety but does so sustainably by leveraging solar power and low-power communication for continuous operation in diverse environments.


## Hypothesis

Our solar-powered smart pedestrian crossing system will automatically detect incoming pedestrians whether or not they are on the crosswalk or not. 

**Measurement Method**: We will go to pedestrian crossing, and in order to test our system, we will cross the road from different locations and at different angles, both inside the crosswalk and outside the crosswalk. Regardless of the angle and location, our LED’s should start flashing to indicate there is someone crossing. 

## Milestones

- [x]  Design, fabricate, and assemble a custom PCB shield incorporating the LoRa module, TP4056 charger, and 3.3V linear regulator. Ensure compatibility with the ESP32 Cam and finalize soldering of external components.

- []  Develop and test code to interface the ESP32 board with the LoRa module using custom SPI pins to ensure communication with the other ESP32 board.
- [x]  Interface individual components (ESP32 Cam, LoRa, Solar, RGB LED Matrix) with the ESP32 Board and test their functionality to ensure proper integration.
- []  Validate the charging efficiency and output stability of the solar-powered TP4056 battery system to ensure reliable power for the ESP32 setup.
- []  Design and print a custom enclosure for the PCB shield to protect the hardware and provide durable housing for outdoor use.
- []  Assemble the full project, including LED strips on the pedestrian crossing sign, and conduct a live demonstration to validate pedestrian detection, warning light activation, and LoRa communication.

## Photos

## Mini Project #3 Tutorial

## Resources


## Video Ideas
- Da Vinci Resolve Free Editing Software
- Start with Title Screen, Problem Statement, and Overview of our Solution
1. Opening (5-10 seconds)
Title Screen: Display project title ("Pedestrian Safety System"), team member names, course info (ECE 196, Fall 2024).
2. Problem Statement & Solution Overview (20-30 seconds)
3. System Design Overview (40-50 seconds)
Slide or Diagram: Show a labeled diagram or graphic of the system, outlining the main components (two ESP32 Cams, RGB LED matrix, LoRa module, solar power).
4. PCB Design & Customization (30-40 seconds)
Footage or Screenshots: Show close-ups of the PCB design and the final prototype.
5. Prototype and Demo (50 seconds - 1.5 minutes)
Footage: Demonstrate the prototype in action, showing both cameras, the RGB LED matrix, and the reaction when a pedestrian or jaywalker is detected.
6. Challenges and Future Improvements (20-30 seconds)
7. Closing (5-10 seconds)
Thank You Screen: “Thank you for watching!” with links to the project’s GitHub or a way to reach out for questions.

[Poster Link](https://docs.google.com/presentation/d/1piVCpWneqZ5gmzYCBuGzzY3xZIutdS-CmckrON2Q2YI/edit?usp=sharing)
   

