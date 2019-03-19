# Indoor Air Quality Monitor Using IOTA

Healthy indoor Environments System of Smart Commercial Buildings using MAM.

## Version 1

The project consists of 3 files and must be executed on the Raspberry Pi:
- sensor.js: Simple test between the Raspberry Pi board and the DHT11 humidity sensor. 
- mam_sensor.js: The DHT11 sensor data is read and published to the Tangle using MAM.
- mam_receive.js: Extract the stored data from the Tangle using MAM and display the data.

## Version 2

The project consists of 5 files:
- sensorArduino.ino: This code is to capture the data of the three sensors: DHT11 humidity and temperature sensor, MQ-2 LPG gas sensor, and MQ-7 CO gas sensor.
- listportsArduino.ino: It shows us the available ports of the Arduino UNO board.
- sensorArduino.js: The DHT11, MQ-2 and MQ-7 sensors data are read and displayed.
- mam_sensorArduino.js: The DHT11, MQ-2, and MQ-7 sensors data are read and published to the Tangle using MAM.
- mam_receiveArduino.js: Extract the stored data from the Tangle using MAM and display the data.



