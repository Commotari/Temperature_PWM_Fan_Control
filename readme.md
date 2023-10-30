
Project: Temperature PWM Fan Control
====================================

Purpose:
------------------------------------

The goal of the project is to create a software and hardware to control standard 4-wire fans based on temperature sensors.

concrete use case:
	in the Strandgut culture club there is a refrigerator/cooling system with multiple drawers with bottles inside that need to be cooled.
  But the waste heat of the system does not have a good way out. That means that there is heat buildup that decreases the eficacy of
  that cooling system. To get rid of the heat buildup we need some fans to blow the heat out of a ventillation grille.
  Additionally the fan speed should be controlled depending on the temperature inside of that cooling system.
expectation: lower electricity bill, better cooling performance, bottles get cold faster in case of restocking the drawers with warm bottles (of beer)
  on days, where the cooling system is more or less at standby, the fans should turn off, or turn on in rare ocations.
  optionally, we can log the temperature every 5 minutes and after two weeks we have a good knowledge about the temperatures inside the cooling system
  and the improvements after using the fans.
  
  
 
 
 
 
Basic features:
------------------------------------

* microcontroller with pwm outout for three fans
* multiple temperature sensors via I2C
* rtc via i2c
* serial interface for debugging and configuration

