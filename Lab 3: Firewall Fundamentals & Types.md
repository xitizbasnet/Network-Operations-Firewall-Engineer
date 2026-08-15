# Lab 3: Firewall Fundamentals & Types

**Difficulty Level:** Beginner | **Duration:** 50 minutes

---

## 🎯 Lab Objective

Master firewall concepts, types, and deployment models. Understand the role of firewalls in network security and learn different firewall architectures.

---

## Task 1: Firewall Types & Architecture Study

### Steps

1. **Study stateless firewall (packet filtering)**
2. **Learn stateful firewall concepts and connection tracking**
3. **Research Next-Generation Firewalls (NGFW) capabilities**
4. **Compare hardware vs software firewall implementations**
5. **Document advantages and limitations of each type**

### Firewall Type Comparison

| Type                 | Mechanism              | Best For            | Limitations        |
| -------------------- | ---------------------- | ------------------- | ------------------ |
| **Packet Filtering** | IP/Port rules          | Basic filtering     | No state awareness |
| **Stateful**         | Connection tracking    | Enterprise networks | Higher CPU usage   |
| **NGFW**             | Deep packet inspection | Advanced threats    | Higher cost        |
| **Cloud-based**      | SaaS model             | Remote workers      | Dependency on ISP  |

---

## Task 2: Firewall Deployment Models

### Steps

1. **Design perimeter firewall placement**
2. **Plan internal segmentation firewall architecture**
3. **Document DMZ (Demilitarized Zone) design**
4. **Create firewall redundancy and failover plan**

---

## 3 Best Practices & Tips

> 💡 **Best Practices & Tips**

* Always deploy firewalls at critical network boundaries (internal/external).
* Use a **DMZ** for any externally-facing services to isolate critical internal infrastructure.
* Implement firewall redundancy (**HA pairs**) for business-critical networks.
* Start with a **"deny all, allow specific"** approach for maximum security.
* Regularly update firewall firmware to patch security vulnerabilities.
* Monitor firewall CPU/memory usage — plan upgrades before hitting capacity.
* Document all firewall policy changes with business justification.
