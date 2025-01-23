# Cellular-network-data-logger
Code for a cellular data logger running on a Pi Pico with micropython
The connections for the data logger can be found as a seperate file.

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
