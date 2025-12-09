**SHESHIELD – A MATERNAL ALERT DEVICE**

**Abstract**
SheShield is a wearable emergency alert pendant designed to enhance women’s safety and provide basic health monitoring in a compact, cost-effective form. The system integrates an Arduino Nano microcontroller, an HC-05 Bluetooth module, a pulse sensor for heart rate monitoring, an RGB LED and buzzer for user feedback, and a manual SOS button. When triggered, the device transmits emergency signals via Bluetooth to a paired smartphone, where the data can be monitored through a Bluetooth terminal application.

The prototype demonstrates reliable Bluetooth communication, effective heart rate tracking, and responsive feedback indicators, showcasing the feasibility of wearable devices for personal safety. While the present version focuses on manual triggering and health monitoring, advanced features such as automatic fall detection, GPS-enabled SMS alerts, and a dedicated Android application with maternal health guidance are proposed for future development. SheShield, therefore, serves as a foundation for a holistic safety and maternal support device, bridging immediate emergency needs with potential long-term wellness applications.

**1. Introduction**
Safety and health monitoring are pressing needs for women, especially in vulnerable conditions such as late-night travel or pregnancy. Delays in accessing help can worsen emergencies. Affordable and wearable solutions can empower users with confidence and immediate support. SheShield is developed as a compact prototype that focuses on providing quick emergency alerts and continuous heart rate monitoring through Bluetooth communication.

**2. Literature Survey**

Women’s safety devices: Most focus on GPS tracking or mobile alerts but often lack affordability and integrated health monitoring.
Wearable health monitors: Widely available but typically limited to fitness applications without SOS features.
IoT in safety: Research shows IoT-enabled systems can improve emergency response, but integrating safety and health into a single device remains underexplored.

**3. Existing Designs**
Mobile apps (e.g., SOS apps) depend on smartphones and may not be accessible during emergencies.
Fitness wearables monitor vitals but lack emergency alert systems.
Standalone SOS devices send alerts but do not offer health monitoring.
-	These gaps highlight the need for a combined, compact solution like SheShield.

**4. Proposed Design**
The SheShield prototype consists of:
Hardware: Arduino Uno / Nano, HC-05 Bluetooth module, pulse sensor, RGB LED, buzzer, SOS push button.

 <img width="830" height="427" alt="image" src="https://github.com/user-attachments/assets/a77ed804-e45c-46a1-8f3f-160a7a22959e" />

**Working Principle:**
  1. When the SOS button is pressed, an alert is sent to the smartphone via Bluetooth.
     
     <img width="232" height="410" alt="image" src="https://github.com/user-attachments/assets/24e916c2-1b1d-405c-9e6e-79a607caaef1" />

  2. The pulse sensor continuously monitors heart rate, and abnormal readings can trigger alerts.
  3. RGB LED and buzzer provide instant feedback to the user.
**Output Monitoring:** Alerts and data are currently viewed using a Bluetooth terminal/controller app on a smartphone. 


**5. Results and Discussion**
**Testing confirmed: **

<img width="268" height="374" alt="image" src="https://github.com/user-attachments/assets/47397d10-27d1-47ad-83c6-4ca62a79cdc0" />

* Reliable Bluetooth connection between pendant and smartphone.
* Accurate heart rate monitoring displayed on Arduino serial monitor.
* Effective user feedback through RGB LED and buzzer on SOS activation.
**Limitations:**
* No direct GPS/SMS functionality yet.
* No fall detection mechanism in the current version.
* Dependence on smartphone Bluetooth range and availability.

**6. Conclusion and Future Scope**
The current SheShield prototype demonstrates that a wearable Bluetooth-enabled device can effectively provide SOS alerts and monitor heart rate with real-time feedback. It serves as a foundation for more advanced systems.
Future Scope includes:
* Fall detection system for automatic emergency alerts.
* Dedicated Android application for GPS-enabled SMS alerts.
* Maternal health guide integration (diet plans, exercise, pictorial guidance).
* GSM/Wi-Fi modules for wider communication range without smartphone dependency.
* Voice-activated SOS trigger and stress detection using combined heart rate and temperature sensing.
* Compact, water-resistant, and durable design for practical everyday use.

**References**
1. Arduino.cc – Official Arduino Documentation.
2. HC-05 Bluetooth Module Datasheet.
3. Pulse Sensor Amped – Official Guide.
4. WHO – *Maternal Health Overview*.
5. R. Kumar, “IoT-based Safety Devices for Women,” *International Journal of Emerging Tech*, 2022.


