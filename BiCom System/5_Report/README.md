# Introduction:
Two-way communication is used in the Bicom system. The receiver performs two-way encryption and verification when the driver carries the smart card key and comes within the designated range. The door will automatically open after verification is completed, and the driver will only need to touch the ignition button to start the vehicle. The entire procedure does not necessitate any key operations. It will also provide the motorist with a new level of safety and comfort.The LF downlink in two-way RF systems is solely used to wake up the key fob and establish the RF up/downlink. During the authentication procedure, the bi-directional RF link handles all communication.

# Research:
The Bicom system is referred regarded as 'Passive' because it does not need the user to take any action. A magnetically coupled radio frequency signal is used to communicate between the key and the automobile. When the key is 'in the car's communication range,' the system believes that it is in close proximity. The system is made up of two parts: a key fob and a vehicle module, both of which contain wireless transceivers that use a magnetically coupled radio frequency signal to detect each other. When the key fob is within range, the vehicle's module sends out encoded messages all the time.
# Requirements
## High Level Requirements
|ID	| DESCRIPTION STATUS |
|---|--------------------|
|HLR1|	The application shall display Window status|
|HLR2|	The application shall display alarm status|
|HLR3|	The application shall display car battery info status|
|HLR4|	The application shall display Door status|
# Low Level Requirements
| ID |	DESCRIPTION STATUS |
|----|---------------------|
|LLR1|	For displaying window status, user need to press the button one time|
|LLR2|	For displaying alarm status , user need to press the button two time|
|LLR3|	For displaying car battery info status, user need to press the button three time|
|LLR4|	For displaying Door status, user need to press the button four time|
# SWOT Analysis
## Strengths
low power consumption

Better Security

Better accesss control

Ease and convenience

## Weakness
The cost of this technology is high

Thieves can hack the program

## 4W'S & 1H
## WHO
The Bicom system is an electronic access control system that can be operated from user.

## WHAT
The Bicom system which are commonly used to displaying window status, alarm status, car battery info status, Door status.

## WHEN
end user needs to perform an action that causes a physical or software key fob to send a radio signal to a receiver that controls an electronic lock.

## Where
Bicom systems for cars can operate in any where with the requirements.

## How
The action is usually performed by pressing a button on a physical fob.
# Applications
## Applications of the Bicom are:

1. Bicom are generally used to remotely lock or unlock doors.
2. Bicom are often employed to secure vehicles from theft, passive keyless entry does not involve any activity on the end user's part.
3. Bicom are used in Auto mobile industries, cars and other vechicles.
4. Bicom systems for automobiles can also operate the vehicle's ignition system, security alarm, horn, lights, and trunk, in addition to locking and unlocking the doors.
5. Bicom can also be used to regulate access to certain portions of a structure, such as garages.
6. Bicom is used in some home automation and security systems.
# Block Diagrams
## Structural
# High Level
<!-- images -->
![dia](https://user-images.githubusercontent.com/98865009/157861800-f1ecc53e-d789-444a-b3c1-79fcbeec1343.png)

# Low Level
<!-- images -->
![dia](https://user-images.githubusercontent.com/98865009/157860944-1b321813-7bd7-469b-b93d-f0e0f6178bb6.png)

## Behavior Diagram
# High Level
<!-- images -->
![dia](https://user-images.githubusercontent.com/98865009/157857855-c2791576-0c8e-4ee2-8811-6f04526c9028.png)

# Low Level
<!-- images -->
![dia](https://user-images.githubusercontent.com/98865009/157856085-8db34286-2ec2-4a34-b0de-4cc6481b7fe3.png)
# TestPlanAndOutput
|NO|	Test case |	Test case Objective |	Input data |	Expected Result |	Actual Result |	status |
|--|--------------|---------------------|--------------|--------------------|-----------------|--------|
|1|	TC-1|	For displaying the window status of car|	user needs to press the button one time|	All LED On at the same time, its shows the window status	|All LED ON at the same time, its shows the window status	|Pass ✅|
|2|	TC-2|	For displaying the alarm status of car|	user needs to press the button Two time|	All led off at the same time, its shows the alarm status|	All led off at the same time, its shows the alarm status	|Pass ✅|
|3|	TC-3|	For displaying the car battery info	|user needs to press the button three time|	All led on in clockwise, it shows the car battery info|	All led on in clockwise, it shows the car battery info|	Pass ✅|
|4|	TC-4|	For displaying the Door status of car|	user needs to press the button four time|	All led on in anti-clockwise , its shows the Door status of car|	All led on in anti-clockwise , its shows the Door status of car	|Pass ✅|
|5|TC-5|	Key fob| acts like a unidirectional RKE system for a car|	Implemented	Successful|Implemented	Successful|Pass ✅|
|6|TC-6|	Car status information|  displayed on the key fob by LED/display	|Implemented|Implemented	Successful|	Pass ✅|
|7|TC-7|	Car Window Status|	Button_Press "1 Time"	|Window Status|	Window Status|	Pass ✅|
|8|TC-8|	Car Alarm Status|	Button_Press "2 Times"|	Alarm Status	|Alarm Status	|Pass ✅|
|9|TC-9|	Car Battery Information Status|	Button_Press "3 Times"|	Battery Status|	Battery Status	|Pass ✅|
|10|TC-10|	Car Door Status	|Button_Press "4 Times"|	Door Status	|Door Status	|Pass ✅|
#  REFERENCE
https://www.researchgate.net/publication/322886970_A_Remote_Controlled_Car_Using_Wireless_Technology
