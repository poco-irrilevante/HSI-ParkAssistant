<header>
	Park Assistant
</header>

<main>

# Version Control

## Change Record

| Copy No | Date | Author | Remarks |
| --------- | --------- | ----------------------- | -------------------------------------------------------------------- |
| v 0.0.1 | 20 June 2017 | Charles Korthout | Initial creation |

## Reviewers

| Date | Name | Function | Remarks |
| --------- | --------- | ----------------------- | -------------------------------------------------------------------- |
|  | |  | | 

## Distribution

# Summary
This project will build an autonomously driving robot car based on Makeblock [Makeblock](http://www.makeblock.com/) components, including 2 MegaPi controllers. They connect to a [Raspberry Pi 3](https://www.raspberrypi.org/products/raspberry-pi-3-model-b/) microcontroller. 
The main aim of the Park Assistance project is to produce a simulation model for some car manufacturer LEPO. The car manufacturer wants to implement a park assistance in his middle-class cars. Due to the fact that the development of this kind of utilities is expensive they decided to create a car model, based on the the above controllers. 
LEPO also considers it, of vital importance, that the data collected during the simulation can be used to tune and refine the ultimate solution that will be implemented in their cars.

# Content

# Introduction

## Objective
### Reverse Parking
### Driving

## Assumptions

## Additional consideration points

### General description

### Product perspective

### General capabilities

## Architectural representation

### Introduction

#### Front lights

#### Blinker Lights

#### Brake / Rear lights

#### Steering 
#####	Servo’s

#### Throttling
##### DC Encoder Motors

#### Sensors
##### Distance Sensors

### Regular car behavior

#### Driving forwards/backwards in a straight line (Throttling)

##### Logical Design
##### Design calculations
##### Development and coding
##### Physical Design
##### Measurements and Tests
##### Code refactoring

#### Turn to the left or right (Steering)

##### Logical Design
##### Design calculations
##### Development and coding
##### Physical Design
##### Measurements and Tests
##### Code refactoring

### Safety regulations

#### The light sensor
##### Logical Design
##### Design calculations
##### Development and coding
##### Physical Design
##### Measurements and Tests
##### Code refactoring

#### The light power control
##### Logical Design
##### Design calculations
##### Development and coding
##### Physical Design
##### Measurements and Tests
##### Code refactoring

#### Front lights	
##### Logical Design
##### Design calculations
##### Development and coding
##### Physical Design
##### Measurements and Tests
##### Code refactoring

#### Bringing it together
##### Logical Design
##### Design calculations
##### Development and coding
##### Physical Design
##### Measurements and Tests
##### Code refactoring

#### Left and Right Blink lights
##### Logical Design
##### Design calculations
##### Development and coding
##### Physical Design
##### Measurements and Tests
##### Code refactoring
##### Code Refactoring (switch tristate)	

###  An obstacle (for example a car) is close to the rear of the car (car must stop moving backwards)
##### Logical Design
##### Design calculations
##### Development and coding
##### Physical Design
##### Measurements and Tests
##### Code refactoring

### Park Assistance
##### Identify a free position to park	
##### Logical Design
##### Design calculations
##### Development and coding
##### Physical Design
##### Measurements and Tests
##### Code refactoring

#### Park maneuvering backwards	
##### Logical Design
##### Design calculations
##### Development and coding
##### Physical Design
##### Measurements and Tests
##### Code refactoring

#### Park maneuvering forward
##### Logical Design
##### Design calculations
##### Development and coding
##### Physical Design
##### Measurements and Tests
##### Code refactoring
	

### Communication	
#### Wireless connectivity	
##### Logical Design
##### Design calculations
##### Development and coding
##### Physical Design
##### Measurements and Tests
##### Code refactoring

####	Data buffering	
##### Logical Design
##### Design calculations
##### Development and coding
##### Physical Design
##### Measurements and Tests
##### Code refactoring

####	Stop car after longer communication drop
##### Logical Design
##### Design calculations
##### Development and coding
##### Physical Design
##### Measurements and Tests
##### Code refactoring

####	Data Collection (normal driving)
##### Logical Design
##### Design calculations
##### Development and coding
##### Physical Design
##### Measurements and Tests
##### Code refactoring

#### Data Collection (Parking)
##### Logical Design
##### Design calculations
##### Development and coding
##### Physical Design
##### Measurements and Tests
##### Code refactoring

###	Security (Startup protection)	
##### Logical Design
##### Design calculations
##### Development and coding
##### Physical Design
##### Measurements and Tests
##### Code refactoring

## Architectural Goals and Constraints
## Car design and Mechanics
### Steering
The steering is based on 4 servo's connected, each connected to a wheel of the car. The used servo MG995 is a simple, often used servo. This version is equiped with a 3-pin cable 
for connection and metal chainwheels. The Makeblock servo purchased at Kiwi electronics [MG995 Standaard Servo Pack](https://www.kiwi-electronics.nl/robotics/robotics-mechanical-parts/makeblock-motors/mg995-standaard-servo-pack) It can be connected with a RJ25 adapter.
The first step is to connect the servo to the bracket.
![ ](./images/Connecting-servo-to-bracket.jpg "Connecting servo to bracket")

### Throttling

### Braking

##	Glossary	
## References
#  Appendix A Install Rasbian on Raspberry Pi
## Enable WiFi hotspot

</main>

