Automated Water Conservation and Management System

This project is an **Arduino-based water level control system** designed to prevent **overflow and water wastage** in polytank storage systems.  
It automatically activates a submersible pump when the water level is low and shuts it off when the tank is full. A **buzzer and LEDs** provide alerts when the tank reaches capacity.  

🚀 Features
- ✅ **Automatic pump control** using a water level sensor  
- ✅ **Overflow prevention** — pump shuts off when tank is full  
- ✅ **Visual + Audio indicators** (LEDs + buzzer)  
- ✅ **Low-cost, scalable solution** for domestic water management  

🛠 Components Used
- Arduino Uno  
- Water level sensor (analog)  
- Mini submersible water pump (via relay/transistor driver)  
- LEDs with resistors (status indicators)  
- Buzzer  
- Jumper wires, breadboard


Key pin mapping:
- **A0** → Water level sensor signal  
- **D7** → Pump control (via relay module or transistor driver)  
- **D6** → LED1 (Pump ON indicator)  
- **D5** → LED2 (Tank full indicator)  
- **D4** → Buzzer (Tank full alert)

Arduino Code
The Arduino sketch is provided in the document dubbed "Arduino Automatic Water Conservation System Sketch"
