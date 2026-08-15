# Lab 4: Linux-Based Firewall Configuration (iptables)

**Difficulty Level:** Intermediate | **Duration:** 90 minutes

---

## 🎯 Lab Objective

Gain hands-on experience configuring Linux firewalls using **iptables**. Learn packet filtering rules, NAT configuration, and firewall policy implementation.

---

## Task 1: iptables Fundamentals & Basic Rules

### Steps

1. **Understand iptables tables (filter, nat, mangle)**
2. **Create basic ACCEPT/DROP rules for specific ports**
3. **Implement stateful connection tracking rules**
4. **Test rules using telnet/nc commands**

### Basic iptables Commands

#### List Current Rules

```bash
iptables -L -n -v
```

#### Create Basic Rule Allowing SSH

```bash
iptables -A INPUT -p tcp --dport 22 -j ACCEPT
```

#### Create Rule Allowing Established Connections

```bash
iptables -A INPUT -m state --state ESTABLISHED,RELATED -j ACCEPT
```

#### Drop All Incoming Traffic (Default Deny)

```bash
iptables -P INPUT DROP
```

---

## Task 2: NAT Configuration & Port Forwarding

### Steps

1. **Configure Source NAT (SNAT) for internal networks**
2. **Implement Destination NAT (DNAT) for port forwarding**
3. **Test NAT rules with internal/external hosts**
4. **Make firewall rules persistent across reboots**

---

## Task 3: Advanced Filtering Rules

### Steps

1. **Implement rate limiting to prevent DoS attacks**
2. **Block spoofed IP addresses and invalid traffic**
3. **Create logging rules for security monitoring**
4. **Document all rules in a firewall policy document**

---

## 3 Best Practices & Tips

> 💡 **Best Practices & Tips**

* Always set default policies (**DROP for INPUT/FORWARD, ACCEPT for OUTPUT**).
* Use connection state tracking for more efficient and secure rule processing.
* Implement rate limiting to protect against DDoS and brute-force attacks.
* Log dropped packets for security auditing and incident investigation.
* Use `iptables-save`/`restore` for rule persistence across reboots.
* Test all rules thoroughly before deploying to production.
* Consider **UFW (Uncomplicated Firewall)** as a user-friendly alternative to raw iptables.
