# Gas-level-monitoring-system
An Iot device that senses the gas levels of hazardous gas in sewage and septic areas. 

This project uses an ESP8266 microcontroller to monitor hazardous gas levels in the environment. It reads data from an MQ-5 gas sensor and sends this data to ThingSpeak for real-time monitoring and analysis.

## Features

- **Real-time Monitoring**: Continuously measures gas levels and sends the data to ThingSpeak.
- **WiFi Connectivity**: Connects to a specified WiFi network to transmit data.
- **Data Logging**: Logs gas level data to ThingSpeak for further analysis.

## Components Used

- **ESP8266**: A low-cost WiFi microchip with full TCP/IP stack and microcontroller capability.
- **MQ-5 Gas Sensor**: A sensor for detecting various gases, including LPG, natural gas, and smoke.
The code initializes the ESP8266, connects to the specified WiFi network, and continuously reads data from the MQ-5 gas sensor. It calculates the gas level as a percentage and sends this data to ThingSpeak every 15 seconds.

ThingSpeak is an Internet of Things (IoT) analytics platform that allows users to collect, visualize, and analyze live data from their connected devices. It provides a robust API for integrating data from sensors and devices, making it easy to build and deploy IoT applications.
