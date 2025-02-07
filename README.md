# Cellular-network-data-logger
Code for a cellular data logger running on a Pi Pico with micropython.

Load the main code and all the libraries to the PI Pico. 

calibration_HX711 is used to get the RAW value and calibration factor for your load cells.
Set_RTC is used to set the RTC time similar to you PC time.
Thermocouple_test s used to test the thermocouple.



Parts required: 

• Microcontroller (Raspberry Pi Pico): Serving as the central processing unit to manage
  data acquisition and transmission.
  
• Micro SD Card Module and Micro SD Card: For local storage of sensor data.

• Cellular Modem (SIM7670E): Eabling reliable data transmission over cellular networks.

• Load Cells and Load Cell Amplifier (HX711): Measuring the weight of wood consumed
  by the cookstove.
  
• Thermocouple (K-Type) and Thermocouple Amplifier (AD8495): Measuring cook-
  stove temperature with high reliability.
  
• Real-Time Clock (PCF8523): Providing accurate timestamps for collected data.

• Power Management Module (Waveshare Solar Power Management Module (D)):
  Ensuring continuous power supply using solar panels and batteries.
  
• Batteries: Three 18650 Li-ion batteries, selected for their energy density and reusability.

• Solar Panels: Two 10W, 12V panels, supplying energy to charge the batteries in remote
  environments.
  
• Voltage Regulator (LM3940): Regulating the voltage from 5V to 3.3V to ensure safe
  operation.

The wiring diagram is as followed:
![wiring_diagramm (1)](https://github.com/user-attachments/assets/9675abd5-8d98-4bf3-b570-91a33c6ad89a)
