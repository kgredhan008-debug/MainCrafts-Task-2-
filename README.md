🚀 Project OverviewThe objective of this project is to create a virtual automation system that detects human motion and triggers a real-time visual alert.
Developer: Promoredhan K G 
Institution: Sri Ramakrishna Institute of Technology, Coimbatore 
Environment: Tinkercad Circuits (Virtual Breadboard Prototyping) 
🛠️ How It Works
The Sensor:
A PIR (Passive Infrared) Sensor monitors changes in infrared radiation. When a person moves within its range, it detects a sharp energy spike and outputs a digital HIGH signal.  The Controller: An Arduino UNO R3 reads this signal. If motion is present (HIGH), it supplies 5V to turn on an LED and sends a log message to the system monitor. 
The Output: A red LED acts as the visual alarm, protected by a 220 Ω resistor to limit current and prevent component damage. 
🔌 Wiring SchemePIR Sensor: VCC to Arduino 5V, GND to Arduino GND, Signal OUT to Digital Pin
2.  LED Alert: Anode (+) to Digital Pin 13 (via 220 Ω resistor), Cathode (-) to Arduino GND. 
