# Vehicle2Vehicle-Communication

The system is implemented using Arduino, MCP2515 transceivers, NEO 6M-001 GPS sensor, Node MCU and a potentiometer. 
The system consists of Two sensor data collection ECUs and a V2I ECU.. Data collection ECU will extract the sensor values and communicate it to the V2I ECU using CAN protocol.
Each of the two sensors used will be interfaced with respective Arduino boards and each such unit will act as sensor data collection ECU.  
The communication takes place over Wi-Fi and Node-MCU is used as V2I ECU. Data collection ECUs provide the required data that is to be transmitted but it has to be formatted properly before it can be communicate.

**GPS information fetching:**

![image](https://github.com/user-attachments/assets/ace642b7-46fe-43bf-844d-10bb269b830e)

**Break Value fetching:**
![image](https://github.com/user-attachments/assets/1310ca08-5d51-4e40-8a1c-c31eb2fdd46d)




