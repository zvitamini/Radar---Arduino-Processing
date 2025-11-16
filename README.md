Radar — Arduino & Processing

This project demonstrates a basic radar system built for educational purposes. It was developed as part of an in-class activity to teach students the fundamentals of sensors, serial communication, and real-time data visualization.

Arduino Code: RADAR/Arduino_Radar

Processing Code: RADAR/Radar

The system uses an Arduino Uno with an ultrasonic sensor to measure distances, while the Processing sketch visualizes the data in real time.

⚠ Important: In the Processing sketch, update the port in the following line to match your Arduino connection before running:

myPort = new Serial(this,"COM6", 9600); // starts the serial communication


Replace "COM6" with your Arduino’s correct port. On macOS or Linux, the port may look like /dev/tty.usbmodem* or /dev/ttyACM0.

Author: zvitamini
Date: November 15, 2025
Purpose: Built with care and dedication for education
<img width="1257" height="726" alt="Radar_Arduino_Circuit" src="https://github.com/user-attachments/assets/711aeab1-c0c1-4515-8b34-b51f4d85d653" />
