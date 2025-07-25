# Air-Quality-Measurement-and-Toxic-Gas-Detection-System
Air pollution is rising rapidly in urban and industrial areas, threatening health and the environment. Our project offers a real-time system to monitor air quality and detect toxic gases, providing instant alerts to help reduce exposure and promote timely action.
<img width="828" height="560" alt="Capture" src="https://github.com/user-attachments/assets/2edad937-2da2-42d5-94a4-1bff89893481" />


### **Air Quality and Toxic Gas Detection System**

#### **Overview**

Air pollution is becoming a critical concern worldwide, especially in urban and industrial regions, where vehicle emissions, industrial discharges, and indoor pollutants are rising at alarming rates. Poor air quality contributes significantly to respiratory diseases, cardiovascular problems, and environmental degradation. To address this issue, our project proposes a **real-time air quality monitoring and toxic gas detection system** capable of continuously tracking pollutant levels and warning users about unsafe conditions.

This system is designed to detect and analyze the concentration of multiple harmful gases using calibrated gas sensors and microcontroller-based processing. With built-in alert mechanisms and display units, users are promptly notified when air quality deteriorates, allowing them to take necessary actions to reduce health risks.

---

### **Major Problems Addressed**

* **Rising Air Pollution:** Continuous increase in emissions from vehicles, factories, and human activities.
* **Lack of Accessible Monitoring:** Most air quality data is available only in centralized government dashboards; users lack localized, real-time updates.
* **Health Hazards:** Long-term exposure to pollutants such as carbon monoxide, ammonia, ozone, and volatile organic compounds (VOCs) can lead to severe health issues.
* **Indoor Pollution Ignored:** Indoor air pollution is often overlooked, yet it can be more harmful due to poor ventilation and concentrated sources of toxins.

---

### **Our Solution**

We have developed a **compact, low-cost, and real-time air quality and toxic gas detection system** that addresses the limitations of traditional monitoring methods. Key features include:

* **Detection of Toxic Gases:** Measures concentration levels of CO, CO₂, O₃, NH₃, Acetone, Toluene, CH₄, and other VOCs.
* **PM2.5 Measurement:** Monitors particulate matter which affects lung health.
* **Real-Time Alerts:** Buzzer and LCD alerts when any gas crosses predefined safety thresholds.
* **User Recommendations:** Informs users about necessary precautions like improving ventilation or activating air purifiers.
* **Data Transmission:** Sends gas concentration data to an ESP32 for wireless communication to mobile apps or cloud platforms for IoT-based analytics.

---

### **Applications**

* **Automobile Cabins:** Ensures in-vehicle air is safe, particularly during heavy traffic or tunnel travel.
* **Homes and Offices:** Monitors indoor air quality to protect inhabitants from gas leaks or poor ventilation.
* **Factories and Labs:** Helps detect dangerous gas leaks or pollution levels to protect workers.
* **Public Buildings:** Can be integrated into smart city infrastructure for community-level environmental monitoring.

---

### **Future Developments**

* **Machine Learning Integration:** Use collected sensor data to predict pollution spikes and recommend preventive actions.
* **Mobile App & Cloud Dashboard:** Remote air quality tracking via smartphone.
* **Automated Ventilation Control:** Trigger air purifiers or ventilation systems based on gas levels.
* **Solar-Powered Versions:** For outdoor, low-maintenance deployments.

---

### **Main Components Used**

* **Microcontroller:** ATmega328 (Arduino Uno) for local processing
* **Gas Sensors:**

  * MQ135 (CO, NH₃, Benzene, VOCs)
  * MQ7 (CO)
  * MQ9 (CO, CH₄, LPG)
  * MQ131 (Ozone)
* **Particulate Matter Sensor:** PM2.5 sensor for dust and airborne particles
* **ESP32 Module:** For wireless IoT communication
* **LCD Display & Buzzer:** For real-time feedback and alerts

---

### **Why Use Microcontrollers in the Design?**

* **Real-Time Processing:** Immediate reading and response to changing air quality.
* **Scalability:** Easy to integrate with new sensors or future modules.
* **Low Power & Cost-Effective:** Ideal for both household and industrial use.
* **Portability:** Compact and easy to deploy in diverse environments.
* **Flexibility:** Reprogrammable for future improvements or specific applications.

---

### **Benefits and Impact**

* **Health Protection:** Helps reduce exposure to harmful gases and improves indoor/outdoor air safety.
* **Supports Environmental Monitoring:** Aids in data collection for research and public awareness.
* **Enhances Smart City Development:** Contributes to intelligent environmental management systems.
* **Educational Use:** Offers a practical tool for learning embedded systems and environmental engineering.
* **Early Warning System:** Prevents hazardous gas exposure through immediate alerts.

