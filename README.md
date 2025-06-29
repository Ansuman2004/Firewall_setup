# Firewall Setup & Basic Management (Windows)

**Objective:** Configure and test basic firewall rules to allow or block traffic on Windows using Windows Defender Firewall.

**Platform:** Windows 10/11

---

## 📌 Steps Performed (Windows GUI)

✅ **1) Opened Windows Defender Firewall**  
- Launched `wf.msc` (Windows Defender Firewall with Advanced Security) via Run.

✅ **2) Listed existing Inbound Rules**  
- Navigated to the Inbound Rules section to capture current firewall configuration.

✅ **3) Added a rule to block Telnet (port 23)**  
- Opened **New Rule** → chose **Port** → entered TCP port `23`.
- Selected **Block the connection** → applied to all profiles → named the rule `Block Telnet (port 23)`.

✅ **4) Verified the block**  
- Confirmed the rule appeared in the Inbound Rules list.
- Attempted to connect to port 23 locally (optional: noted failure or lack of Telnet client).

✅ **5) Added a rule to allow SSH (port 22)**  
- Opened **New Rule** → chose **Port** → entered TCP port `22`.
- Selected **Allow the connection** → applied to all profiles → named the rule `Allow SSH (port 22)`.

✅ **6) Documented with screenshots**  
- Captured screenshots at each step for submission.

---

## 📝 Summary

A firewall inspects and filters network traffic using rules for ports and protocols.
- Blocking port 23 protects from insecure Telnet connections.
- Allowing port 22 enables secure SSH access (if needed).

Through Windows Defender Firewall, we learned how to create, verify, and remove inbound rules, demonstrating basic firewall management and understanding of traffic filtering.

---

## 📁 Screenshots

- **main_window.png**: Windows Firewall main interface.
- **before_rules.png**: List of inbound rules before adding new ones.
- **after_rules.png**: “Block Telnet (port 23)” and “Allow SSH (port 22)” rules created.

---

## ✅ Key Concepts Learned

- Firewall configuration basics  
- Port-based traffic filtering  
- Importance of blocking insecure services (Telnet)  
- Using Windows Defender Firewall’s GUI effectively

---
