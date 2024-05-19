# Automotive Electronics - Course Project 

### Problem Statment : Crash Detection and Spot Warning system
## Description
The  Crash Detection and Alert System for Automotive Electronics is designed to enhance vehicle safety by leveraging advanced sensor technologies, GPS, and cloud computing. When a crash occurs, the system immediately sends an alert to the cloud, which then notifies nearby emergency services. Simultaneously, the vehicle's GPS coordinates are tracked to provide precise location data. The cloud also maintains a database of accident-prone zones. If a vehicle approaches one of these zones within 200 meters, the system warns the driver via the infotainment system. Should the vehicle exceed the speed limit in these zones, the system automatically disengages the accelerator to maintain a safe speed. This comprehensive approach ensures timely assistance during accidents, alerts drivers about potential hazards, and enforces speed limits in high-risk areas, significantly enhancing overall road safety.

## Literature Survey
From the Litreature survey we found that the main sensors needed for Crash Detection are: <br /> 


**GPS Module** : 
- The GPS module captures the precise location data during a crash. <br />
- By continuously tracking the speed and movement of the vehicle, the GPS module can help in determining the impact of the crash.<br /> 
- The GPS module records essential data, such as the vehicle's path, speed, and position before, during, and after the crash. 

**Vibration Sensor** : 
- Vibration sensors used in crash detection are highly sensitive and capable of detecting sudden, high-magnitude vibrations indicative of a collision. <br />
-  This sensitivity allows for the rapid identification of crash events, triggering safety mechanisms such as airbags and emergency response systems almost instantaneously.<br /> 


To Find the Papers we Reasearched on for our problem Statement,[ Click Here.](https://github.com/JadenEkbote/crashDetection.github.io/tree/main/resarch)



## Methodology

The IoT-Based Crash Detection and Alert System is developed through the following key phases:

1. **System Design**: Identify requirements, design system architecture, and plan hardware-software integration.

2. **Hardware Integration**: 
   - Install and calibrate crash detection sensors.
   - Integrate GPS modules for real-time location tracking.
   - Interface with the vehicle’s ECU for speed control.

3. **Software Development**:
   - Develop embedded software for real-time crash detection.
   - Set up a cloud platform for alert management and data storage.
   - Implement secure communication protocols (e.g., MQTT, HTTP).

4. **Crash Detection Algorithm**: Process sensor data to detect crashes and generate alerts.

5. **Cloud Services**:
   - Manage crash alerts and notify emergency services.
   - Maintain a database of accident-prone zones.

6. **Proximity Alert System**: 
   - Monitor vehicle proximity to accident-prone zones using GPS.
   - Display warning messages on the infotainment system when nearing high-risk areas.

7. **Speed Control Mechanism**:
   - Monitor vehicle speed in accident-prone zones.
   - Automatically disengage the accelerator if speed exceeds the limit.

8. **Testing and Validation**:
   - Conduct unit and integration testing.
   - Perform real-world field testing for system validation.

9. **Deployment and Maintenance**:
   - Install the system in vehicles.
   - Provide ongoing monitoring and updates for reliability.

This methodology ensures a robust, efficient, and reliable system for enhancing vehicle safety and timely accident response.



## Block Diagram
The Block Diagram for the Crash Detection:


<img width="505" alt="Block Diagram" src="https://github.com/JadenEkbote/crashDetection.github.io/assets/97228905/3f19a8aa-582e-404f-975e-e7f4afcb129b">

## Flowchart
The Flow Chart for the Crash Detection and alert system:




<img width="500" alt="Flow chart" src=https://github.com/JadenEkbote/crashDetection.github.io/assets/97268081/bf95886f-91e4-493f-9d34-a79183255b56>


