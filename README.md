# Wireless-Based-Data-Transmission-System-for-Gate-Control-in-Dams-along-with-Data-Analysis

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
![lora connection](https://github.com/aaditi2/Wireless-Based-Data-Transmission-System-for-Gate-Control-in-Dams-along-with-Data-Analysis/assets/114819269/f2f78fbb-df9a-4e38-b4cb-ec44e7e69e64)

![cuplikan_web_23-12-2022_51015_easyeda_com_oTzaOI1WMD](https://github.com/aaditi2/Wireless-Based-Data-Transmission-System-for-Gate-Control-in-Dams-along-with-Data-Analysis/assets/114819269/0be9126b-fd49-4611-a769-e5207080c7c4)

![lora111_1pguqn8req_neNPR3ciIO](https://github.com/aaditi2/Wireless-Based-Data-Transmission-System-for-Gate-Control-in-Dams-along-with-Data-Analysis/assets/114819269/2405c51e-1584-46d9-a950-d0af369c4fbc)

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
