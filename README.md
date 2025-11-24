# Wireless EV Charging Station
This project simulates a wireless EV charging system using Arduino and Proteus. An ultrasonic sensor detects vehicle arrival and activates a relay to start wireless charging through inductive coils. An LED and LCD display show the charging status with complete Arduino code and Proteus simulation included.
## System Demonstrates
- Vehicle arrival detection
- Wireless charging activation
- Real-time LCD status display
- Relay-based load control
- Proteus simulation + Arduino code
## Hardware Components Used
- Arduino UNO
- Ultrasonic Sensor (HC-SR04)
- Relay Module
- Wireless Power TX-RX Coil Set
- Transistor (2N2222A)
- LEDs and resistors
- Jumper wires
- 16x2 LCD (non-I2C)
## Software Tools
- Arduino IDE
- Proteus 8 Professional
## Working Principle
1. Ultrasonic sensor measures distance continuously.
2. When vehicle is within threshold (<50 cm), detection is triggered.
3. Arduino activates the relay to start wireless charging.
4. LED glows indicating charging.
5. LCD displays: “Vehicle Detected”, “Charging Started”, “Charging Stopped”.
## How to Run the Project
### In Proteus
- Open the .pdsprj file.
- Load the .hex file into Arduino.
- Run simulation.
- Adjust potentiometer/object to test detection.
### In Real Hardware
- Upload main.ino to Arduino.
- Connect ultrasonic sensor, relay, LED, and LCD as per schematic.
- Power the system.
- Bring an object/vehicle close to start charging.
## Applications
- Smart EV charging stations
- Wireless charging demonstrations
- Automatic parking + charging systems
- IoT-based energy management (future version)
