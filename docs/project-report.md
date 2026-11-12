> Converted from the submitted Word document for GitHub reading. Student IDs removed; wording, team credits and embedded figures retained. Original pagination and Word formatting are not reproduced.

Project Summary

Project Overview

This project uses an Arduino board, PIR motion sensor a LED a resistor and a breadboard to create a simple motion detection system. The main goal is to detect motion in front of the PIR sensor and send the detection to the LED.

Environment Used

The project was developed using the Arduino IDE for coding and a breadboard-based hardware setup for circuit implementation. The system operates in a standard indoor environment where human motion can be detected by infrared radiation changes.

Purpose of the Project

To demonstrate basic sensor integration with a microcontroller and real-time control of output devices. It helps in understanding digital input/output operations and a sensor behavior and simple automation concepts.

How the Project Operates

The PIR sensor continuously monitors the surrounding area for motion. When motion is detected the sensor outputs a HIGH signal to one of the Arduino’s digital input pins. The Arduino program reads this signal and immediately turns the LED ON. When no motion is detected the sensor output becomes LOW and the Arduino turns the LED OFF.

Future Improvements

The project can be improved by adding multiple LEDs or buzzers for different alert levels. Wireless communication modules such as WiFi or Bluetooth can be added to send motion alerts to a mobile application. A camera module could also be integrated for visual verification. Additionally, combining this system with light sensors can make it more intelligent by activating only in lowlight conditions.

Applications

This project has practical applications in multiple domains. In home automation, it can be used for automatic lighting systems where lights turn on only when someone enters a room, saving energy. In healthcare, similar systems can monitor patient movement, especially for elderly care, to detect activity or inactivity. In industrial environments, motion detection can improve security by identifying unauthorized access to restricted areas. In smart buildings, it can be integrated with alarm systems or occupancy detection systems to optimize power usage or with glass moving doors.
