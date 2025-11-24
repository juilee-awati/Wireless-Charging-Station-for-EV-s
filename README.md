# Wireless-Charging-Station-for-EV-s: 
This project simulates a wireless EV charging station using Arduino and Proteus. An ultrasonic sensor detects vehicle arrival, activating a relay to start wireless charging through inductive coils. An LED and LCD display show real-time charging status. Includes complete Arduino code and Proteus simulation.

#The system demonstrates:
Vehicle arrival detection
Wireless charging activation
Real-time status display on LCD
Relay-based load control
Proteus simulation + Arduino code

#Hardware Components used:
Arduino UNO / Nano
Ultrasonic Sensor (HC-SR04)
Relay Module
Wireless Power TX-RX Coil Set
Transistor (2N2222A)
LEDs & Resistors
Jumper Wires
16x2 LCD (without I2C module)

#Software Tools:
Arduino IDE
Proteus 8 Professional

#Working Principle:
1. Ultrasonic sensor continuously measures distance.
2. When a vehicle comes within the threshold range (e.g., < 20 cm), detection is triggered.
3. Arduino activates the relay to start wireless charging.
4. LED glows to indicate charging process.
5. LCD displays the live status:
    “Vehicle Detected”
    “Charging Started”
    “Charging Stopped”

#How to Run the Project-

In Proteus:
Open the *.pdsprj file from ProteusFiles folder.
Load the compiled .hex file to the Arduino inside Proteus.
Run simulation.
Move potentiometer / vehicle model to test distance detection.

In Real Hardware:
Upload the main.ino file using Arduino IDE.
Connect ultrasonic sensor, relay, and LED as per schematic.
Power the system.
Place an object/vehicle near the sensor to initiate charging

Applications:
Smart EV Charging Stations
Wireless Charging Demonstrations
Automatic Parking + Charging Systems
IoT-based Energy Management (future version)
