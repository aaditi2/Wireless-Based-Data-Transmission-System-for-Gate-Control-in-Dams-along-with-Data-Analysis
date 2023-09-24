# Wireless-Based-Data-Transmission-System-for-Gate-Control-in-Dams-along-with-Data-Analysis
Combination of- Hardware (Arduino, ultrasonic sensors, LoRa) and Software (Python, ML). This project was sponsored by CWPRS (Central Water and Power Research Station), Pune, India, and led by Dr. Selva Balan, Joint Director and Scientist at CWPRS.


User Manual Group. 27 (2022-2023)

Hardware steps:
1. Fill the tank with water upto 20cms on one side of the partition.
2. Connect Arduino UNO with Ultrasonic sensor, LoRa transmitter and LoRa antenna module using the following connections.

Connections: 
LoRa SX1278 Module           Arduino UNO Board
3.3V                               3.3V
Gnd                                 Gnd
En/Nss                              D10
G0/DIO0                             D2
SCK                                 D13
MISO                                D12
MOSI                                D11
RST                                 D9

3. Connect Arduino UNO with LoRa’s receiver module with antenna using the same connection as that of LoRa’s transmitter module servo motor with the following connections:
-> The servo motor has a female connector with three pins. The darkest or even black one is usually the ground.
-> Connect the power cable that in all standards should be red to 5V on the Arduino.
-> Connect the remaining line on the servo connector to a digital pin on the Arduino.
   
4. Fix the servo motor to the stand using a clamp, wound and tie a thread to the cap(attached to the motor) and tie the other end of the thread to the metallic gate.
5. Insert the gate inside the wooden slit.
   
Software manual:
1.Open Arduino IDE and upload and run the code with the file extension ‘tx.ino’ on the transmission side.
2. 1.Open Arduino IDE and upload and run the code with the file extension ‘rx.ino’ on the receiving side.
3.The gate operation will be performed.
4. Open the serial window to observe the output.
