# Digital Twin Dashboard to Monitor Battery Performance
Digital Twin Dashboard for real-time battery performance monitoring using ESP32, sensors and IoT.

## About the Project

This is a college mini project developed to monitor battery performance in real time using an ESP32 and IoT-based dashboard.

The system collects battery parameters such as voltage, current and temperature and displays the data through a digital dashboard.

##  Objectives

- Monitor battery voltage in real time
- Measure charging and discharging current
- Monitor battery temperature
- Estimate battery State of Charge (SOC)
- Display battery performance through a dashboard
- Enable remote monitoring using Wi-Fi

##  Technologies Used

- ESP32
- INA219 Current/Voltage Sensor
- Temperature Sensor
- IoT
- Wi-Fi
- Dashboard
- Arduino IDE
- C/C++

##  Working

1. The battery is connected to the sensing circuit.
2. Voltage and current are measured using the INA219 sensor.
3. Battery temperature is monitored using a temperature sensor.
4. ESP32 collects the sensor data.
5. ESP32 sends the data through Wi-Fi.
6. The dashboard displays the battery parameters in real time.
7. Battery SOC is estimated from the measured data.

##  Parameters Monitored

| Parameter | Purpose |
|---|---|
| Voltage | Battery voltage monitoring |
| Current | Charging/discharging monitoring |
| Temperature | Overheating detection |
| SOC | Battery charge estimation |

##  Future Scope

- Battery State of Health (SOH) prediction
- Remaining Useful Life (RUL) estimation
- AI/ML-based fault detection
- Cloud data storage
- Mobile notifications
- Cell-level battery monitoring
- EV battery pack monitoring

##  Author

Karmugilan M.  
B.E. Electrical & Computer Engineering  
Sona College of Technology
