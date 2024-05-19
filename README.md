# AE - Course Project 

### Problem Statment : Crash Detection System
***Description***:
This project focuses on the development of an IoT-based Crash Detection and Alert System designed to enhance vehicle safety and provide timely assistance during accidents. The system leverages modern sensor technologies, GPS, and cloud computing to detect crashes, alert emergency services, and warn nearby vehicles of accident-prone zones.

System Workflow
The system operates through a series of interconnected processes, each playing a crucial role in ensuring the overall functionality and efficiency of the crash detection and alert mechanism. The workflow is described below:

Start:

The system is initialized and begins monitoring for potential crashes using onboard sensors.
Crash Detection:

Decision Point: The sensors continuously monitor the vehicle for signs of a crash.
Yes: If a crash is detected, the system proceeds to send an alert to the cloud.
No: If no crash is detected, the system continues monitoring.
Send Alert to Cloud:

Upon detecting a crash, the system immediately sends an alert message to the cloud server, containing crucial data about the incident.
Alert Nearby Services:

The cloud server processes the alert and dispatches notifications to nearby emergency services, ensuring timely assistance.
Track Location using GPS:

The system retrieves the GPS coordinates of the accident location and sends this information to the cloud for precise location tracking.
Accident Prone Zone Information:

The cloud maintains a database of accident-prone zones. It updates the database with new incidents, helping in identifying high-risk areas.
Approaching Accident Prone Zone Detection:

Decision Point: The system continuously monitors the vehicle’s location.
Yes: If the vehicle approaches an accident-prone zone within 200 meters, the system triggers a warning message.
No: If the vehicle is not near an accident-prone zone, the system continues monitoring.
Display Warning Message:

The system sends a warning message to the vehicle’s infotainment system, alerting the driver of the upcoming accident-prone zone.
Check Speed Limit:

Decision Point: The system monitors the vehicle’s speed.
Exceeds Limit: If the vehicle’s speed exceeds the limit, the system proceeds to disengage the accelerator.
Within Limit: If the speed is within the limit, the system continues monitoring.
Disengage Accelerator:

To ensure safety, the system sends a command to the ECU to disengage the accelerator, maintaining the speed below the limit.
End:

The system continues to monitor and manage vehicle speed, ensuring compliance with safety protocols.
Features
Real-Time Crash Detection: Utilizes advanced sensors to detect crashes instantaneously.
Immediate Alert System: Sends alerts to the cloud, which in turn notifies emergency services and contacts.
GPS Tracking: Accurately tracks and transmits the location of the vehicle.
Accident Prone Zone Alerts: Warns drivers when approaching known high-risk areas.
Speed Monitoring and Control: Ensures the vehicle remains within safe speed limits in accident-prone zones.
Technologies Used
Sensors: For crash detection.
GPS: For location tracking.
Cloud Computing: For processing alerts and managing accident data.
ECU (Engine Control Unit): For controlling vehicle speed.
Infotainment System: For displaying warning messages to the driver.
Conclusion
This IoT-based Crash Detection and Alert System integrates multiple technologies to provide a comprehensive solution for vehicle safety. By enabling real-time crash detection, immediate alerts to emergency services, and proactive warnings about accident-prone zones, this system aims to reduce response times and prevent further accidents, ultimately saving lives and enhancing road safety.

***Litrature Survey***:
From the Litreature survey we found that the main sensors needed for Crash Detection are: <br /> 


**GPS Module** : 1. The GPS module captures the precise location data during a crash. <br /> 
2. By continuously tracking the speed and movement of the vehicle, the GPS module can help in determining the impact of the crash.<br /> 
3. The GPS module records essential data, such as the vehicle's path, speed, and position before, during, and after the crash. 

**Vibration Sensor** : 1. Vibration sensors used in crash detection are highly sensitive and capable of detecting sudden, high-magnitude vibrations indicative of a collision. <br /> 
2. This sensitivity allows for the rapid identification of crash events, triggering safety mechanisms such as airbags and emergency response systems almost instantaneously.<br /> 


[Literature Survey](https://github.com/JadenEkbote/crashDetection.github.io/tree/main/resarch)



***Block Diagram***:
The Block Diagram for the Crash Detection:


<img width="505" alt="Block Diagram" src="https://github.com/JadenEkbote/crashDetection.github.io/assets/97228905/3f19a8aa-582e-404f-975e-e7f4afcb129b">

***Flowchart***:
The Flow Chart for the Crash Detection and alert system:




<img width="500" alt="Flow chart" src=https://github.com/JadenEkbote/crashDetection.github.io/assets/97268081/bf95886f-91e4-493f-9d34-a79183255b56>


