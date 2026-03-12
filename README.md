# Enterprise Endpoint Security Lab – Microsoft Intune & Microsoft Defender for Endpoint

## 1. Project Overview

This project demonstrates a **hands-on enterprise endpoint security implementation** using Microsoft cloud security technologies. The lab simulates how organisations manage identities, devices, and endpoint protection using **Microsoft Entra ID, Microsoft Intune, and Microsoft Defender for Endpoint**.

The objective of this lab was to configure a secure environment that includes:

- Identity and access management
- Endpoint device management
- Endpoint detection and response (EDR)
- Security policy enforcement
- Vulnerability management
- Phishing and web protection

This project reflects **real-world cybersecurity operations used by IT and SOC teams to secure enterprise devices.**

---

# 2. Technologies Used

| Technology | Purpose |
|------------|--------|
| Microsoft Entra ID | Identity and access management |
| Microsoft Intune | Device management and policy enforcement |
| Microsoft Defender for Endpoint | Endpoint detection and response |
| Microsoft Defender SmartScreen | Web and phishing protection |
| Microsoft Defender Antivirus | Malware protection |
| Microsoft Defender Vulnerability Management | Patch and vulnerability monitoring |

---

# 3. Lab Architecture

## Environment Setup

- Microsoft 365 E5 Tenant  
- Windows Virtual Machines  
- Cloud Identity Management  
- Endpoint Protection Monitoring  


---

# 4. Implementation Steps

## 1️⃣ Identity and Access Management

Created **users and security groups** in **Microsoft Entra ID**.

Configured:

- User accounts
- Security groups

Created user accounts and security groups in Microsoft Entra ID to simulate **enterprise identity and access management**. 
![Entra Users](https://github.com/piang077/Microsoft-End-Point-Security-Lab/blob/main/ScreenShots/allusertask3.png)
![Groups](https://github.com/piang077/Microsoft-End-Point-Security-Lab/blob/main/ScreenShots/windowhrgroupcreated.png))

---

## 2️⃣ Virtual Machine Deployment

Created **Windows Virtual Machines** and configured them to:

- Join the organisation's **Entra ID domain**
- Allow user authentication using enterprise credentials

This replicates **corporate endpoint onboarding.**

![Virtual Machine](https://github.com/piang077/Microsoft-End-Point-Security-Lab/blob/main/ScreenShots/test1-2vm.png)
![Join Entra ID Domain](https://github.com/piang077/Microsoft-End-Point-Security-Lab/blob/main/ScreenShots/test1-2devices.png)

---

## 3️⃣ Device Enrollment into Intune

Devices were enrolled into **Microsoft Intune** for **centralised endpoint management.**
This allows organisations to **manage devices remotely and enforce security standards.**

![Enrollment Into Intune](https://github.com/piang077/Microsoft-End-Point-Security-Lab/blob/main/ScreenShots/test1-2onintune.png)

---

## 4️⃣ Microsoft Defender for Endpoint Integration

Enabled and connected **Microsoft Defender for Endpoint**.

Configured **endpoint onboarding** so devices report telemetry to the **Defender Security Portal**.

![Enable Intune Connection](https://github.com/piang077/Microsoft-End-Point-Security-Lab/blob/main/ScreenShots/enableintuneconnection.png)
![Enable Defender for endpoint](https://github.com/piang077/Microsoft-End-Point-Security-Lab/blob/main/ScreenShots/enablewindowdefenderforendpoint.png)
![Onboarded Defender for endpoint](https://github.com/piang077/Microsoft-End-Point-Security-Lab/blob/main/ScreenShots/onboardonendpointintune.png)


---

# 5. Endpoint Security Policies

Configured multiple **enterprise security policies** in **Microsoft Intune.**

---

## Antivirus Protection

Implemented **Microsoft Defender Antivirus** policies including:

- Real-time protection
- Scheduled scanning
- Cloud-delivered protection

---

## Firewall Protection

Configured **Windows Defender Firewall policies** to control **inbound and outbound traffic.**

Purpose:

- Reduce attack surface
- Prevent unauthorized network access

---

## Attack Surface Reduction (ASR)

Configured **Attack Surface Reduction rules** to block common malware techniques.

Examples:

- Block Office applications from creating child processes
- Prevent credential theft
- Block executable content from email attachments

---

## SmartScreen and Phishing Protection

Enabled **Microsoft Defender SmartScreen**

Features enabled:

- Malicious website blocking
- Phishing protection
- Application reputation checking

---

# 6. Conditional Access

Configured access policies using **Microsoft Entra ID**.

Examples:

- Allow login **only from compliant devices**
- Enforce **device compliance checks**

This ensures **only secure and managed devices can access company resources.**

---

# 7. Vulnerability and Patch Management

Used **Microsoft Defender Vulnerability Management** to identify missing security updates.

Performed:

- Patch monitoring
- Vulnerability assessment
- Security recommendations

This demonstrates **basic vulnerability management and patching processes used by enterprise security teams.**

---

# 8. Security Monitoring

Using the **Microsoft Defender Security Portal**, monitored:

- Device security status
- Vulnerability exposure
- Threat alerts
- Endpoint security posture

This simulates **SOC monitoring of enterprise endpoints.**

---

---

# 10. Key Skills Demonstrated

This project demonstrates practical experience in:

- Identity and Access Management
- Endpoint Security
- Endpoint Detection & Response (EDR)
- Vulnerability Management
- Security Policy Implementation
- Microsoft Security Stack
- Device Compliance and Conditional Access

---

# 11. Real-World Relevance

This lab simulates **enterprise endpoint security operations** commonly performed by:

- SOC Analysts
- Endpoint Security Engineers
- IT Security Administrators
- IT Support Security Teams

It demonstrates the **end-to-end lifecycle of securing corporate devices**, from **identity onboarding to endpoint threat protection**.

---

