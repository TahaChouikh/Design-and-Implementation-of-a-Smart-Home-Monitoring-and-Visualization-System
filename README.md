# Design and Implementation of a Smart-Home Monitoring and Visualization System
This project involves the design and implementation of a smart home monitoring system using two sensor nodes. The first node utilizes an ESP32 microcontroller paired with a DHT22 sensor to capture temperature and humidity data, while the second node consists of an ESP32 microcontroller with a BH1750 sensor for measuring light intensity.

Both sensor nodes transmit data to a Raspberry Pi 4 using the MQTT or Matter protocol. The Raspberry Pi stores the collected data in an InfluxDB database, and the Grafana application is used to visualize the measurements on a dashboard in real-time. This system provides a user-friendly interface for monitoring environmental conditions within a smart home setup.
