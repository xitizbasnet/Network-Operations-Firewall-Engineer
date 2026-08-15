# Lab 5: Windows Firewall Configuration & Management

**Difficulty Level:** Intermediate | **Duration:** 75 minutes

---

## 🎯 Lab Objective

Master Windows Firewall configuration, including inbound/outbound rules, profiles, and Group Policy management. Learn to enforce security policies at scale.

---

## Task 1: Windows Firewall GUI Configuration

### Steps

1. **Access Windows Defender Firewall with Advanced Security**
2. **Configure inbound rules for critical services (RDP, HTTP, HTTPS)**
3. **Create outbound rules to restrict suspicious protocols**
4. **Test rules using telnet and netstat commands**

---

## Task 2: Group Policy Firewall Management

### Steps

1. **Create firewall policies using Group Policy Editor (`gpedit.msc`)**
2. **Deploy rules to organizational units via Active Directory**
3. **Implement domain profile, private profile, and public profile rules**
4. **Monitor policy compliance across multiple endpoints**

---

## Task 3: PowerShell Firewall Automation

### Steps

1. **Create firewall rules using PowerShell commands**
2. **Develop script to audit firewall configuration**
3. **Implement automated rule deployment across servers**
4. **Create monitoring alerts for rule changes**

---

## 3 Best Practices & Tips

> 💡 **Best Practices & Tips**

* Use **Group Policy** for consistent firewall deployment across the enterprise.
* Leverage Windows Firewall profiles (**Domain, Private, Public**) appropriately.
* Regularly audit firewall rules to remove unnecessary and orphaned rules.
* Enable firewall logging for troubleshooting and security auditing.
* Implement connection security rules for server-to-server communication encryption.
* Test rules in a test environment before deploying to production.
* Monitor firewall rule changes to detect unauthorized modifications.
