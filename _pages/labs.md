---
title: "Lab Challenges"
layout: single
permalink: /labs/
author_profile: true
---

# 🔬 Lab-Based Challenges

## 💻 Cyber Hygiene CTF

### Problem:
Phishing simulation and defense analysis.

### Approach:
- Analyzed a suspicious link  
- Used `CyberChef` for base64 decoding  
- Reviewed HTTP headers via Burp Suite

### Tools:
CyberChef, Burp Suite, Wireshark

### Screenshot:
![Phishing Flag](../assets/images/phishing_lab.png)

### Lessons:
- Always inspect suspicious traffic  
- Learn to decode payloads manually

---

## 🐚 Linux Privilege Escalation

### Problem:
Find a way to become root on a misconfigured Ubuntu box

### Tools:
`linpeas.sh`, `GTFOBins`, `sudo -l`

### Lesson:
SUID binaries + PATH abuse = root access
