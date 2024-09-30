# BMS-for-drone

1. The aim for this project was to develop a Battery Management System (BMS) for autonomous drones, especially those involved in obstacle avoidance, package delivery, surveys, monitoring, and disaster management, etc.
2. Bonka (11.1V 4500mAh 35C 3s Li-Po) is the battery used for drone’s operations. The LV BMS is connected to battery and monitors the voltage, current and temperature for the battery using the sensors and using the ADC peripheral of the microcontroller these values will be calculated and transmitted to the flight controller. If these values are not within range the power is not transmitted further and error code is sent to flight controller
3. Furthermore the BMS will check for the following:
      over charge and over discharge
      over current
      short circuit
4. And lastly the DC-DC converters will act and provide the adequate voltage required for each module (5v to jetson nano and flight controller and 12 v to solenoid).
5. Since drone’s are supposed to be light weight an in-house pcb will be designed with the aim of being compact and robust.

