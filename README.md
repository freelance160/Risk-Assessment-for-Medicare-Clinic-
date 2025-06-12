# 🛡️ Risk Assessment Scenario Task: Medicare-Clinic

**Scenario: Risk Assessment for "MediCare Clinic"**

MediCare Clinic is a small healthcare practice with 10 employees, including doctors, nurses, and an office administrator. They store patient records in a cloud-based Electronic Health Records (EHR) system and use an in-office Wi-Fi network. Employees use desktops and mobile devices to access patient information.

Task:
-Identify, evaluate, and document potential risks for MediCare Clinic, following these steps:

-Create an asset inventory (List key assets such as EHR software, office Wi-Fi, employee devices, etc.).

-Identify potential threats (Think of cyber and physical threats like ransomware, unauthorized access, or insider threats).

-Rate the risk (Use High, Medium, or Low based on impact and likelihood).

-Suggest risk mitigation strategies (How can the clinic reduce these risks? Think of security controls like encryption, MFA, security awareness training, etc.).
---

## 📋 Asset Inventory

| **Asset**                | **Description**                                                                          |
|--------------------------|------------------------------------------------------------------------------------------|
| Employee Desktops        | Used by employees to access patient data and medical records.                           |
| EHR software system      | Stores patient data and medical records.                                                |
| Email System (Office 365)| Used for communication with patients and internal team collaboration.                   |
| Patient Medical Records  | Confidential medical information of patients protected by HIPAA                         |
| Office Wi-Fi Network     | Used to connect employee devices to the internet and EHR system.                        |
| Employee Mobile Devices  | Used for accessing patient information when away from the desktop                       |

---

## 🚨 Threat Identification

| **Asset**                | **Threats**                                                                              |
|--------------------------|-------------------------------------------------------------------------------------------|
| Employee Desktops        | Phishing, malware                                                                         |
| EHR software system      | Unauthorized access, patient data breach                                                  |
| Email System (Office 365)| Phishing, business email compromise                                                       |
| Patient Medical Records  | Theft, data exfiltration, unauthorized access by internal and external threat actors, ransomware |
| Office Wi-Fi Network     | Unauthorized access, weak encryption, rogue access points                                 |
| Employee Mobile Devices  | Unauthorized access, lost device, theft                                                   |

---

## ⚠️ Risk Assessment (Impact and Likelihood)

| **Asset**                | **Threat**                          | **Impact** | **Likelihood** | **Risk Rating** |
|--------------------------|-------------------------------------|------------|----------------|-----------------|
| Employee Desktops        | Phishing                            | High       | High           | High            |
| Employee Desktops        | Malware                             | High       | Medium         | High            |
| Email System (Office 365)| Phishing                            | High       | Medium         | High            |
| Email System (Office 365)| BEC                                 | High       | Medium         | High            |
| EHR software system      | Patient data breach                 | High       | High           | High            |
| EHR software system      | Unauthorized access                 | High       | High           | High            |
| Patient Medical Records  | Ransomware                          | High       | Medium         | High            |
| Patient Medical Records  | Unauthorized access (internal)      | Medium     | Medium         | Medium          |
| Patient Medical Records  | Unauthorized access (external)      | High       | Medium         | High            |
| Office Wi-Fi Network     | Weak encryption                     | High       | High           | High            |
| Office Wi-Fi Network     | Rogue access points                 | High       | Medium         | High            |
| Employee Mobile Devices  | Unauthorized access                 | High       | Medium         | High            |
| Employee Mobile Devices  | Lost device                         | High       | Medium         | High            |
| Employee Mobile Devices  | Theft                               | High       | Medium         | High            |

---

## 🔧 Risk Mitigation Strategies

| **Threat**                        | **Recommended Mitigation**                                                                 |
|----------------------------------|--------------------------------------------------------------------------------------------|
| Phishing (Desktops, Email system)| Conduct monthly phishing training and seminars for all staff members.                      |
|                                  | Enable email filtering and phishing detection tools                                        |
| Malware (Desktops)               | Mandatory and automated software updates                                                   |
|                                  | Restrict admin privileges                                                                  |
|                                  | Install endpoint protection software                                                       |
| Unauthorized access to EHR       | Enforce Multi Factor Authentication (MFA)                                                  |
|                                  | Apply Role Based Access Control (RBAC)                                                     |
|                                  | Regularly audit access logs                                                                |
|                                  | Mandatory change of all passwords every 3 months                                           |
| Unauthorized wifi access         | Use WPA3 encryption                                                                        |
|                                  | Disable default admin credentials on routers                                               |
|                                  | Segment guest network from staff network                                                   |
| Lost device, theft (Mobile)      | Remote security wipe                                                                       |
|                                  | Encryption of all mobile devices                                                           |
|                                  | Storage lockers for devices not in use or being recharged                                  |
| Ransomware                       | Multiple regular backups of patient and hospital data (on-premise and cloud mix)           |

---
