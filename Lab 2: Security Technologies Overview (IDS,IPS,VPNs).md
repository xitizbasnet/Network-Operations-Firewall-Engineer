# Lab 2: Security Technologies Overview (IDS,IPS,VPNs)

**Difficulty Level:** Intermediate | **Duration:** 60 minutes

---

## 🎯 Lab Objective

Understand major security technologies including **Intrusion Detection Systems (IDS)**, **Intrusion Prevention Systems (IPS)**, and **Virtual Private Networks (VPNs)**. Learn their roles in network defense.

---

## Task 1: IDS/IPS Deployment & Configuration

### Steps

1. **Understand IDS vs IPS differences and use cases**
2. **Research Suricata/Snort IDS/IPS tools**
3. **Plan IDS/IPS placement in network topology**
4. **Create detection rules for common attacks**
5. **Document alert and response procedures**

---

## Task 2: VPN Architecture & Configuration Planning

### Steps

1. **Understand VPN types (Site-to-Site, Remote Access)**
2. **Research VPN protocols (IPSec, SSL/TLS, WireGuard)**
3. **Design VPN topology for remote teams**
4. **Plan encryption and authentication mechanisms**
5. **Document VPN access control policies**

---

## Technology Overview

| Technology | Purpose               | Detection/Prevention      | Implementation Complexity |
| ---------- | --------------------- | ------------------------- | ------------------------- |
| **IDS**    | Detect intrusions     | Detection Only            | Medium                    |
| **IPS**    | Prevent intrusions    | Detection + Prevention    | Medium-High               |
| **VPN**    | Secure communications | Encryption/Authentication | Medium                    |
| **WAF**    | Protect web apps      | Application layer         | Medium-High               |

---

## 3 Best Practices & Tips

> 💡 **Best Practices & Tips**

* Deploy IDS/IPS in strategic network segments (DMZ, internal network perimeter).
* Use IPS sparingly — configure aggressive rules only after thorough testing.
* Regularly update IDS/IPS signature databases to detect the latest threats.
* Implement VPN with strong encryption (AES-256) and perfect forward secrecy.
* Monitor VPN logs for unauthorized access attempts and anomalies.
* Use multi-factor authentication for VPN access to critical systems.
* Regularly audit IDS/IPS alerts to fine-tune detection rules and reduce false positives.
