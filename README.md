Wireless Charging Station for EVs

This project simulates a wireless EV charging station using Arduino and Proteus. An ultrasonic sensor detects vehicle arrival, activating a relay to start wireless charging through inductive coils. An LED and LCD display show real-time charging status. Includes complete Arduino code and Proteus simulation.

The system demonstrates:

Vehicle arrival detection

Wireless charging activation

Real-time status display on LCD

Relay-based load control

Proteus simulation + Arduino code

Hardware Components Used:

Arduino UNO / Nano

Ultrasonic Sensor (HC-SR04)

Relay Module

Wireless Power TX-RX Coil Set

Transistor (2N2222A)

LEDs & Resistors

Jumper Wires

16x2 LCD (without I2C module)

Software Tools:

Arduino IDE

Proteus 8 Professional

Working Principle:

Ultrasonic sensor continuously measures distance.

When a vehicle comes within the threshold range (< 20 cm), detection is triggered.

Arduino activates the relay to start wireless charging.

LED glows to indicate charging process.

LCD displays: “Vehicle Detected”, “Charging Started”, “Charging Stopped”.

How to Run the Project
In Proteus:

Open the .pdsprj file from ProteusFiles.

Load the compiled .hex file into Arduino inside Proteus.

Run the simulation.

Move potentiometer / vehicle model to test distance detection.

In Real Hardware:

Upload main.ino using Arduino IDE.

Connect ultrasonic sensor, relay, LED, and LCD as per schematic.

Power the system.

Place an object/vehicle near the sensor to initiate charging.

Applications:

Smart EV Charging Stations

Wireless Charging Demonstrations

Automatic Parking + Charging Systems

IoT-based Energy Management (future version)
