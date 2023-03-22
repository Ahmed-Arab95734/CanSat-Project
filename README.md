# CanSat-Project
CanSat is an educational satellite that make the individuals apply some parts of the Space Mission Concept, its primary objective is to have a good knowledge of how to design a mission and understand its requirements. 
Our CanSat Mission is to determine:

1- Temperature 5- Humidity
2- Pressure 6- Air Quality
3- Acceleration & Orientation 7- Altitude
4- Position (Longitude and Latitude) 8- Magnetic Field (compass)
And all these data stored in SD Card & transmit wirelessly to the ground station throw RF module.
We worked on four subsystems (four teams) and integrated them together to achieve CanSat,
those are:
A. Coding Team
To measure each parameter we have mentioned before, we used a combination of sensors and
electrical devices, Selection of this combination undergoes some limitations:
- Availability in Egypt
- Impact on total budget
We used OOP to create library for each sensor to make writing the main program sketch easy and
manageable.
These Sensors and Electrical devices are:
- ATMEGA 328p microcontroller as the brain of CanSat.
- GPS NEO 6M to Determine CanSat Location (Longitude, Latitude and Altitude).
- 10 DOF-IMU to detect Acceleration, Orientation, Magnetic Field and Pressure
- 433 MHz RF for wireless communication.
- MQ-7 to measure Air Quality.
- DHT-11 to detect surrounding environment of the humidity and temperature.
- SD-Card Module to store all data from all sensors periodically
