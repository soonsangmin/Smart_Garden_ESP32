# Smart_Garden_ESP32

1. System Architecture

<img width="597" height="422" alt="image" src="https://github.com/user-attachments/assets/e2550e84-390a-4baf-b059-0070a1e2cc85" />

   •	Sensor block: The sensor block in an Automatic Temperature, Soil Moisture, and Plant Irrigation Measurement System is responsible for capturing environmental data through various sensors. Each type of sensor serves a specific function related to monitoring the conditions necessary for plant growth.
   
   •	MCU block: The MCU block serves as the brain and coordinator of the entire system, orchestrating the interactions between sensors, actuators, user interfaces, and communication channels. Its role is crucial in transforming raw data into intelligent actions, maintaining system autonomy, and ensuring the effective operation of the Automatic Temperature, Humidity, and Plant Irrigation Measurement System.
   
   •	Relay block: The relay block is a critical component that enables the irrigation system to operate efficiently, conserve resources, and respond dynamically to environmental conditions. It acts as the interface between the MCU and the physical components of the irrigation system, ensuring precise and controlled water delivery to support plant growth.
   
   •	Screen block: The screen block is the user-facing component of the system, providing an intuitive and interactive interface for users to monitor, configure, and control the Automatic Temperature, Soil Moisture, and Plant Irrigation Measurement System. It enhances the user experience by presenting information in a comprehensible manner and enabling users to actively participate in the care of plants.
   
   •	Power: Providing the necessary electrical energy for the system's components to operating.
   
2. ESP32 WROOM 32 - 38PIN

  ESP32 Bluetooth Wi-fi transceiver RF kit is integrated with antenna and RF, energy saving, stable operation, good anti-interference, this is the lowest cost solution for a project with a circuit using 2.4Ghz Wi-Fi and Bluetooth TSMC low power 40nm technology.

  <img width="226" height="226" alt="image" src="https://github.com/user-attachments/assets/787f42c8-6c06-4c41-856c-fca3c381146f" />
  
  •	Power voltage (USB): 5V DC
  •	Input/Output voltage: 3.3V DC
  •	Power consumption: 5μA in suspension mode
  •	Performance: Up to 600 DMIPS
  •	Frequency: up to 240MHz
  •	Wi-fi: 802.11 B/g/n/E/I (802.11N @ 2.4 GHz up to 150 Mbit/s)
  •	Bluetooth: 4.2 BR/EDR BLE 2 control modes
  •	Memory: 448 Kbyte ROM, 520 Kbyte SRAM, 6 Kbyte SRAM on RTC and QSPI Flash/SRAM chip support
  •	USB-Serial chip: CP2102
  •	Digital GPIO: 24 pins (some pins are input only)
  •	Digital Analog: 12bit SAR type ADC, supports measurements on up to 18 channels, some pins support an amplifier with gain programming
  •	Security: IEEE 802.11, including WFA, WPA/WPA2 and WAPI
  •	Hardware accelerated cryptography: AES, SHA-2, RSA, Elliptical Curve cryptography (ECC), Random number generator (RNG)
  •	Pinout:
  
  <img width="550" height="344" alt="image" src="https://github.com/user-attachments/assets/77483a59-8afd-4416-a263-83b3a1369f0e" />

3. Circuit diagram

   <img width="600" height="470" alt="image" src="https://github.com/user-attachments/assets/bed68b00-37d9-4d92-9c45-069f61fbf395" />

4. Flow chart

   <img width="598" height="703" alt="image" src="https://github.com/user-attachments/assets/b37f614c-328e-4455-99e1-44c87861bf24" />


