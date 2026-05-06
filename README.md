# 🔥 Firewall & Intrusion Detection System (IDS) Project

## 📌 Overview

This project demonstrates a **Firewall + Intrusion Detection System (IDS) lab environment** designed to monitor network traffic, detect malicious activities, and enforce security controls in a simulated SOC (Security Operations Center) setup.

It simulates real-world cyber defense scenarios such as port scanning, brute-force attacks, and suspicious network behavior detection using open-source security tools.

---

## 🎯 Objectives

* Design and implement firewall-based network traffic filtering
* Detect malicious activities using IDS concepts
* Monitor and analyze network packets in real time
* Simulate common cyberattacks in a controlled lab environment
* Generate logs for incident response and security analysis

---

## 🛠 Tools & Technologies

* Kali Linux (Attack simulation environment)
* Firewall (iptables / system firewall rules)
* Wireshark (Packet analysis)
* Nmap (Network scanning & reconnaissance)
* Hydra (Brute force attack simulation)
* Log monitoring tools

---

## 🏗 System Architecture

```
Attacker Machine (Kali Linux)
        ↓
Network Traffic (Simulated Attacks)
        ↓
Firewall Layer (Traffic Filtering Rules)
        ↓
IDS Monitoring Layer (Detection & Analysis)
        ↓
Log Generation & Alert System
```

---

## ⚙️ Implementation Workflow

### 1. Firewall Configuration

* Configured firewall rules to allow/deny specific ports and traffic
* Blocked suspicious IP addresses and unauthorized access attempts

### 2. Network Monitoring

* Captured live packets using Wireshark
* Analyzed inbound and outbound network traffic patterns

### 3. Intrusion Detection

* Identified abnormal network behavior patterns
* Detected repeated authentication failures and scanning activity

### 4. Attack Simulation

Performed controlled attacks in a lab environment:

* Port Scanning using Nmap
* Brute Force Login attempts using Hydra

### 5. Logging & Analysis

* Generated system logs for all network activities
* Analyzed logs to identify attack patterns and anomalies

---

## 🚨 Attack Scenarios

### 🔍 1. Port Scanning Attack

* Tool: Nmap
* Purpose: Identify open ports and exposed services
* Result: Multiple scan attempts detected and logged by firewall/IDS layer

### 🔐 2. Brute Force Attack

* Tool: Hydra
* Purpose: Attempt multiple login credentials
* Result: Repeated failed login attempts detected and flagged

### 📡 3. Traffic Analysis

* Tool: Wireshark
* Purpose: Inspect packet-level network behavior
* Result: Suspicious traffic patterns identified

---

## 📊 Key Features

* Real-time network traffic monitoring
* Firewall-based access control
* Intrusion detection simulation
* Attack scenario testing environment
* Log-based security analysis

---

## 📸 Screenshots

![Firewall Rules](firewall.png)
![Firewall Rules](firewall1.png)
![Firewall Rules](firewall2.png)
![Firewall Rules](firewall3.png)
![Firewall Rules](firewall4.png)
![Firewall Rules](firewall5.png)
![IDS Alert](kali.png)
![IDS Alert](kali1.png)
![IDS Alert](kali2.png)
![IDS Alert](kali3.png)
![IDS Alert](kali4.png)
![IDS Alert](kali5.png)

---

## 📚 Key Learnings

* Fundamentals of network security and defense mechanisms
* Firewall rule configuration and traffic filtering
* Intrusion detection and log analysis techniques
* Hands-on experience with cyberattack simulation
* Understanding SOC workflow and incident response basics

---

## 📈 Security Mapping (Advanced)

* Port Scanning → Reconnaissance phase (MITRE ATT&CK)
* Brute Force → Credential Access (T1110)
* Traffic Analysis → Network Monitoring & Detection

---

## ⚠️ Disclaimer

This project is developed strictly for **educational purposes only** in a controlled lab environment. No real-world systems were targeted or harmed.

---

## 👩‍💻 Author

**Tanvi Dinesh Chaudhari**
Cybersecurity Student | SOC & Pentesting Enthusiast

---

## 🚀 Future Enhancements

* Integration with SIEM tools (Splunk / ELK Stack)
* Automated alerting system
* Machine Learning-based anomaly detection
* Advanced threat intelligence integration
