# GSM-based-Plant-and-Pump-Monitoring-System-Using-LPC2129

Description:
This program uses the LPC2129 ARM7 microcontroller to monitor soil moisture and control a water pump through GSM communication.

The user can send SMS commands to check soil moisture status and turn the water pump ON. The system displays the status on an LCD and sends SMS responses.

Features:
Monitors soil moisture using a soil moisture sensor.
Sends soil status (DRY/WET) through SMS.
Controls the water pump using GSM commands.
Displays system status on an LCD.
Automatically turns OFF the pump after 60 seconds.
SMS Commands
SMS Command	Function
status	Checks soil moisture status
pump on	Turns ON the water pump for 60 seconds

Hardware Used:
LPC2129 ARM7 Microcontroller
GSM Module
Soil Moisture Sensor
LCD Display
DC Water Pump
Motor Driver

Header Files:
delay_header.h
uart_header.h
gsm_header.h
lcdheader.h
Motor.h
Motor.c

Working:
The system receives SMS commands through the GSM module. Based on the received command, it checks soil moisture or controls the water pump. The corresponding status is displayed on the LCD and sent back to the user through SMS.
