# sensor_monitoring-IoT-Project Overview
Description:
This project is a real-time environmental monitoring system built with an Arduino Uno and a TMP36 temperature sensor. It measures ambient temperature and displays the output on a 16x2 LCD screen. The system is designed to demonstrate how analog sensors can be integrated with digital displays for automation and monitoring purposes.
Hardware Components:
Arduino Uno Microcontroller
TMP36 Temperature Sensor
16x2 LCD Display
10k Potentiometer
220 Ohm Resistor
Breadboard and Jumper Wires
Circuit Connections
Temperature Sensor: The middle output pin is connected to Arduino Analog Pin A0.
LCD Control: Register Select (RS) is connected to Pin 7, and Enable (E) is connected to Pin 6.
LCD Data: Pins D4, D5, D6, and D7 are connected to Arduino Digital Pins 5, 4, 3, and 2 respectively.
Power: The circuit operates on a 5V supply and Ground provided by the Arduino board.
Contrast Control: The Potentiometer is connected to the LCD V0 pin to adjust text visibility.
Real World Utility
This prototype serves as the foundation for several professional applications including:
Smart Home Automation: Controlling air conditioning and heating systems based on room temperature.
Industrial Safety: Monitoring high-performance machinery to prevent overheating and equipment failure.
Healthcare Storage: Ensuring medical refrigerators maintain the correct temperature for vaccines and medications.
Agriculture: Managing the environment within greenhouses to optimize crop growth.
Implementation Steps
Assemble the hardware according to the circuit diagram.
Connect the Arduino Uno to a computer via USB.
Open the source code in the Arduino IDE.
Verify that the LiquidCrystal library is included in the project.
Upload the code to the board and monitor the LCD for temperature readings.
Adjust the potentiometer if the text on the screen is not clearly visible.
This project is a part of my  virtual internship program at "SoftGrowTech".This project is developed as part of a Software Engineering study to explore the intersection of hardware interfacing and real-time data processing.
