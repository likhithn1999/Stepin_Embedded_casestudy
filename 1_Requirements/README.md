# Requirements
## Objective
The Objective of this Project/Activity is to Develop a user friendly heating system for seats of vehicles and to control the heating range of individual seat.
## Introduction
The Vehicle Seat Heater or Seat Heating Monitoring System is capable of generating mild heat in Seats, In this project a sensor (Pressure/Weight) placed at 
each seats in the vehicles, which tells us that passenger is sat on the perticular Seat or not. If the Passenger is seated then passenger need to set the
tempearature accordingly (this tells us, paasenger switched on the heater). Based on these factors our controller generates heating capabality to seats.
After that LCD Display should show the value of seat heater provided by the passenger through a nobe.Our project usually preffered in European contries,
where temperature is too low.
## Feature
+ The system uses Sensors to access the information about the paasenger is seated or not.
+ Each seat should have a nobe to control/monitor the range of heat.
+ A LCD display shows the temperature of Seat heater.
+ Low cost
# SWOT analysis - Strength, Weakness, Opportunities and Threats
## Strengths
+ Individual heating systems for each Seats.
+ Can easily alter the temperature range.
+ USer friendly.
+ Low cost and Robust system.
## weakness
+ Usually prefferd in Countries where temperatures are too low.
+ Engine should be on to initiate this activity.
+ More number of sensors required if the vehicle have more seats.
## Threats
+ Use chances are less in High temperature places.
+ We can't Turn it on before the passanger/person sitting on the seat.
# 4W's AND 1H
## What
+ This Project concerned on providing mild heating Facility to the passenger via Seats.
## Where
+ Prefferd in Automobiles and or Automotive Industries
## Why
+ To maintain HEALTH in normal/stable state.
## When
+ At low temperature regions
## How
+ By generating a variable heat
# High level and low level Requirement
# High level Requirement 
|ID	  |Description                                                                                               |	 Category|	  Status   |
|-----|----------------------------------------------------------------------------------------------------------|-----------|-------------|
|HR01	|Sensor should give output(LED Turn on or Off)whether the person is seated or not in the vehicle           |  Automatic|	IMPLEMENTED|
|HR02	|Temperature sensor should toggle the temperature	                                                         |  Automatic|	IMPLEMENTED|
|HR03	|Temperature is beyond threshold then turn Off or on AC                                                    |  Manual	 |  IMPLEMENTED|  
|HR04	|display Temperature Value on LCD Screen                                                                   |  Automatic|	IMPLEMENTED|
|HR05	|Exit from the system when Vehicle is not moving	                                                         |  Automatic|	IMPLEMENTED|

# Low level Requirement
|ID  |Description		                                                            |Status      |
|----|--------------------------------------------------------------------------|------------|
|LR01|	Sensor output(LED Turn on or Off) will be in boolean form either 0 or 1	| IMPLEMENTED|
|LR02|	System will tell user that temperature is switching		                  | IMPLEMENTED|
|LR03|  user have to turn on or off the vehicle AC		                          | IMPLEMENTED|
|LR04|	System will display the temperature value inside the vehicle		        | IMPLEMENTED|
|LR05|	System will stopped working once vehicle is Stopped		Not               | IMPLEMENTED|
