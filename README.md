<pre>Battery Management System (BMS) for Smart Energy Monitoring

Overview
This project involves the development of a microcontroller-based Battery Management System (BMS) designed to monitor and protect Li-ion battery packs in real-time. The system measures voltage, current, and temperature, providing live feedback and safety management through embedded logic.

Technologies & Components
1)Microcontroller: Arduino Uno/Nano
2)Sensors:
    i)ACS712 Current Sensor
    ii)LM35 Temperature Sensor
    iii)
3)Display: 16x2 LCD Module
4)5V Single Channel Relays
5)Buzzer
6)Lipo Battery Pack
7)5V Fan
8)Software: Embedded C (Arduino IDE)

Features
1)Real-Time Monitoring of voltage, current, and temperature
2)Auto-cutoff using relay to prevent unsafe conditions
3)User Interface using LCD to show system status

How It Works
1)Voltage is measured using a voltage divider and mapped to actual battery voltage.
2)Current is read from the ACS712 sensor (analog input).
3)Temperature is tracked using LM35 and compared to a safe threshold.
4)Embedded logic checks for:
    Voltage > V_max → Cutoff
    Voltage < V_min → Cutoff
    Current > I_max → Cutoff
5)System updates values live on LCD and serial monitor.</pre>

Circuit diagram

![image alt](https://github.com/arya-manohar-16/Battery-Management-System/blob/main/image.png?raw=true)
