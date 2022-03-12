# About RKE REMOTE KEYLESS ENTRY:
# Description :
A smart entry system is an electronic lock that controls access to a building or vehicle without using a traditional mechanical key. The term keyless entry system originally meant a lock controlled by a keypad located at or near the driver's door, which required entering a predetermined (or self-programmed) numeric code. Such systems now have a hidden touch-activated keypad and are still available on certain Ford and Lincoln models.The term remote keyless system (RKS),also called keyless entry or remote central locking,refers to a lock that uses an electronic remote control as a key which is activated by a handheld device or automatically by proximity. Widely used in automobiles, an RKS performs the functions of a standard car key without physical contact. When within a few yards of the car, pressing a button on the remote can lock or unlock the doors, and may perform other functions. A remote keyless system can include both a remote keyless entry system (RKE), which unlocks the doors, and a remote keyless ignition system (RKI), which starts the engine. Remote keyless entry (RKE) system is a system designed to remotely lock or unlock access to automobiles.

RKE transmission requires two components - a transmitter and a receiver.

* Transmitter - RKE key fob, other ID device with RKE integrated
* Receiver - Body Control ECU, other ECU with integrated RKE
RKE operates by broadcasting radio waves on a particular frequency unidirectionally. RKE systems implement encryption and rolling code algorithms to prevent car thieves from intercepting and spoofing the telegrams. Typical RKE functions are:

# Requirements
## Current Scenario :
* Remote keyless entry (RKE) systems have become extremely popular.
* The installation rate for RKE systems in new vehicles is more than 80% in North America and more than 70% in Europe.
* Besides the obvious advantages of convenience, RKE-actuated vehicle-immobilization technology minimizes car theft.
* European automakers are incorporating the technology in vehicles in cooperation with insurance companies, who in turn, require it as a condition for acquiring auto insurance.
* That trend began in Germany, and is expected to spread throughout Europe within a few years.
* Remote keyless entry (RKE) has captivated automobile buyers, as evidenced by the popularity of RKE on new automobiles and as an after-market item.
* This application note provides an overview of RKE systems and discusses how they meet requirements such as range, battery life, reliability, cost, and regulatory compliance.
* It shows some circuits and design approaches and offers some predictions for future systems, which will include two-way communications.
## High level Requirements :
|ID	|Description|	Category|
|---|-----------|-----------|
|HLR01|	User should able to lock the car|	Technical|
|HLR02|	User should able to unlock the car|	Technical|
|HLR03|	User should able to activate alarm|	Technical|
|HLR04|	User should able to deactivate alarm|	Technical|
|HLR05|	User should able to approach lights|	Technical|
## Low Level Requirements :
|ID|	Description	|Status|
|--|----------------|------|
|LLR01|	STM32 should be able to run on PC	|implemented|
|LLR02|	Hex file must be run without any error|	implemented|
|LLR03|	Delay should be properly added in code|	implemented|
|LLR04|	Static keywords are used|	|implemented|
|LLR05|	Functions to single click	|implemented|
|LLR06|	Functions to double click	|implemented|
|LLR07|	Functions to triple click	|implemented|
|LLR08|	Functions to quard click	|implemented|
## SWOT Analysis :
## swot

## 4 W's and 1 H :
### Who:
The project can be used almost by all people which wants to buy new car having such features as well as who wants to upgrade over traditional methods.At the end,user satisfaction and earier use of technology is the goal of this project.

### What:
RKE (Remote Keyless Entry) System is one of type of automation in car. RKE-actuated vehicle-immobilization technology minimizes car theft and lots of features like for locking and unlocking the door. Activating or deactivating alarms as well as also used to light up car-inner lights.

### When:
when we have parked the car at unsafe place as well as it can also be used to find car in a huge parking point. This project is also used at night time when there is no lightwe can light up the inside car lights. The project can be used inside as well as outside the car.

### Where:
The project can be used inside as well as outside the car.

### How:
Car will lock when switch press once • Car will unlock when Blue switch press two times • To set alarm activation/deactivation when Blue switch press three times • For to approach light when Blue switch press four times