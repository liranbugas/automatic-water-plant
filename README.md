1.	Introduction

  a.	In 05/03/2022 in Or Yehuda I wanted plants in my house.
  
  b.	There are many benefits for plants inside the house:
  
    i.	Filtering the air by reducing dust and chemicals.
    
    ii.	Increasing the moisture and oxygen in the room.
    
    iii.	Adding more naturalistic and welcoming style in the room.
    
  c.	But there is a problem of watering the plant for many lazy people or people who not always sleep in this house. 
  d.	The solution for this is to make a reliable and autonomous mechanism that water the plants but without over watering them.
  e.	This project solves this problem with using stm32 microcontroller for getting better precision and beneficial power consumption.
  
2.	Goal
  a.	Create an autonomous mechanism that water and monitor the plants inside the house.
  b.	 Create a mechanism that is beneficial for power and water consumption.
  c.	Learn voltage and power limitations of electronics. 
  
3.	Components
  a.	A 12V battery box.
  b.	A stm32f103c8t6 microcontroller.
  c.	A capacity soil moisture sensor.
  d.	A 12V water pump.
  e.	A 3V to 12V step up converter.
  f.	A 12V to 5v step down converter.
  g.	A matrix.
  h.	Arduino cables.
 
4.	Schematics
  a.	A0 use as analog input from the sensor (over 2260 is dry soil).
  b.	B9 use as digital output to activate the pump for 4 seconds.
  c.	Wait for 10 seconds between each measure.
  
5.	Optional for expansion
  a.	For powering the pump using external power supply you can use transistor mosfet as gate and Zener diode as  voltage saparator.
