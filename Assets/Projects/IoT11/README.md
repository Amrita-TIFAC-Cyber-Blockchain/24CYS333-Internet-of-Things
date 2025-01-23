# 24CYS333 - Internet of Things
![](https://img.shields.io/badge/Batch-22CYS-lightgreen) ![](https://img.shields.io/badge/UG-blue) ![](https://img.shields.io/badge/Subject-IoT-blue)
<br/>
![](https://img.shields.io/badge/Lecture-2-orange) ![](https://img.shields.io/badge/Practical-3-orange) ![](https://img.shields.io/badge/Credits-3-orange) <br/>

## IoT#11 - IoT-Based Comprehensive Elderly Monitoring System with Integrated Fall Detection and Emergency Alert Mechanism

![](https://img.shields.io/badge/Member-Burla_Rushyendra_Reddy-gold)  ![](https://img.shields.io/badge/Member-Palakurty_Roopak_Naga_Venkata_Sree_Sai-gold)  ![](https://img.shields.io/badge/Member-Yallanuru_Kishan_Sai-gold)  
![](https://img.shields.io/badge/SDG-3-darkgreen) ![](https://img.shields.io/badge/SDG-9-darkgreen) ![](https://img.shields.io/badge/SDG-11-darkgreen)  
<!--![](https://img.shields.io/badge/Reviewed-06th_Jan_2025-brown)-->

---

### Problem Statement
Elderly individuals face heightened risks of falls and medical emergencies due to age-related health issues, reduced mobility, and chronic conditions. Timely assistance is critical, yet traditional systems fail to provide real-time monitoring and effective emergency responses, especially in independent living scenarios.

---

### Proposed Solution

The proposed **IoT-Based Comprehensive Elderly Monitoring System** incorporates real-time monitoring, fall detection, and emergency alert mechanisms, ensuring enhanced safety for elderly individuals. Key features include:

1. **Fall Detection:** Leveraging the MPU 6050 accelerometer and gyroscope for precise motion sensing.
2. **Emergency Alert Mechanism:** Integration of audible alarms, SMS notifications, and cloud-based monitoring for instant response.
3. **Manual Distress Alert:** A panic button for users to signal emergencies.
4. **Cloud Connectivity:** Remote monitoring via NodeMCU ensures caregivers have access to real-time data.

---

### Hardware Requirements

| Component                  | Functionality                                                                                               |
|----------------------------|-------------------------------------------------------------------------------------------------------------|
| Arduino UNO                | Microcontroller for processing sensor data from accelerometer and gyroscope.                               |
| MPU 6050 Shield            | Motion and orientation detection to identify falls.                                                        |
| GSM/GPRS Module (NEO-6M)   | Sends SMS alerts during emergencies.                                                                       |
| NodeMCU                    | Cloud integration for IoT connectivity.                                                                    |
| Buzzer                     | Audible alert during emergencies.                                                                          |
| Touch Sensor               | Panic button for manual distress signaling.                                                                |
| 2500mAH Power Bank/Battery | Portable power source for uninterrupted operation.                                                         |
| LED Indicators             | Visual cues for system status.                                                                             |

---

### Literature Survey

#### IoT in Elderly Care
IoT advancements enable real-time health monitoring and emergency management systems tailored for aging populations. Wearable sensors combined with cloud analytics provide actionable insights, ensuring timely interventions.

* **Source:** IoT Applications in Healthcare Systems, IEEE, 2023.

#### Motion Analysis with MPU 6050
Widely used in fall detection systems, the MPU 6050 offers high precision in motion sensing. Combined with threshold algorithms or machine learning, it ensures accurate fall identification.

* **Source:** Sensor Fusion Techniques in Wearable Devices, Elsevier, 2022.

#### GSM Modules in IoT
GSM modules ensure communication during emergencies, especially in areas with limited internet connectivity, making them critical in IoT applications for elderly care.

* **Source:** IoT for Emergency Management, Springer, 2023.

#### User-Centric Design
Panic buttons and auditory/visual indicators improve usability for elderly populations, ensuring systems are intuitive and accessible.

* **Source:** Design Principles for Aging Populations, Human Factors Journal, 2021.

---

### Mapping the Project to Sustainable Development Goals (SDGs)

| SDG | Alignment                                                                                     |
|:----|:---------------------------------------------------------------------------------------------|
| Goal 3 - Good Health and Well-Being | Enhancing safety and response mechanisms for aging populations.                             |
| Goal 9 - Industry, Innovation, and Infrastructure | Leveraging IoT innovations to support smart, sustainable solutions.                        |
| Goal 11 - Sustainable Cities and Communities | Promoting inclusivity and support systems for aging urban populations.                  |

### Collaboration
| Team | Module & Scope |
|:----:|:---------------|
| [IoT#01](https://github.com/Amrita-TIFAC-Cyber-Blockchain/24CYS333-Internet-of-Things/tree/main/Assets/Projects/IoT01) | IoT-Driven Smart Ambulance System for Real-Time Traffic Management and Emergency Response Optimization | 
| [IoT#22](https://github.com/Amrita-TIFAC-Cyber-Blockchain/24CYS333-Internet-of-Things/tree/main/Assets/Projects/IoT22) | IoT-Based System to mitigate traffic congestion for emergency vehicles. |

---

### References
- Ren, L., & Peng, Y. (2019). Research of Fall Detection and Fall Prevention Technologies: A Systematic Review. IEEE Access. Institute of Electrical and Electronics Engineers (IEEE). http://doi.org/10.1109/access.2019.2922708
- Department of Computer Engineering ,BV(DU)COE, Pune, India., Garg*, D. K., Rao, G., & Department of Computer Engineering, BV(DU)COE, Pune, India. (2020, April 30). An IoT Based Fall Detection System. International Journal of Innovative Technology and Exploring Engineering. Blue Eyes Intelligence Engineering and Sciences Engineering and Sciences Publication - BEIESP. http://doi.org/10.35940/ijitee.f3917.049620  
- Mahesh, G., & Kalidas, M. (2023, November 23). A Real-Time IoT Based Fall Detection and Alert System for Elderly. 2023 International Conference on Advances in Computation, Communication and Information Technology (ICAICCIT). IEEE. http://doi.org/10.1109/icaiccit60255.2023.10465914
- Hasan, N., & Ahmed, M. F. (2024, January). Wearable Technology for Elderly Care: Integrating Health Monitoring and Emergency Alerts. (D. F. H. Sadok, Ed.), Journal of Computer Networks and Communications. Wiley. http://doi.org/10.1155/jcnc/5593708
