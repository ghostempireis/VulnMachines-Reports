# 🤖 Mr. Robot: 1 - Penetration Testing Report

This folder contains a detailed penetration testing report for the vulnerable machine **Mr. Robot: 1**, hosted on **VulnHub**. The machine simulates a real-world CTF challenge inspired by the Mr. Robot TV series. It focuses on web vulnerabilities, enumeration, and privilege escalation techniques.

---

## 📌 Machine Details

- **Name:** Mr. Robot: 1  
- **Platform:** VulnHub  
- **IP Address:** 192.168.164.129  
- **Difficulty Level:** Beginner – Intermediate  
- **OS:** Linux  
- **CTF Objective:** Capture the three hidden flags

---

## 🧰 Tools Used

| Tool             | Purpose                              |
|------------------|--------------------------------------|
| Netdiscover       | Network discovery                    |
| Nmap              | Port scanning and service detection  |
| DirBuster         | Directory brute-forcing              |
| Nikto             | Web server vulnerability scanning    |
| WPScan            | WordPress vulnerability scanning     |
| Hydra             | Brute-forcing credentials            |
| Burp Suite Pro    | Web proxy and request tampering      |
| Python & Netcat   | Reverse shell and privilege testing  |

---

## 🧪 Vulnerabilities Exploited

- Unsecured WordPress access
- Sensitive file exposure (`robots.txt`)
- Credential brute-force
- Command injection & reverse shell
- Privilege escalation via misconfigured services

---

## 📄 Files

| File Name              | Description                                   |
|------------------------|-----------------------------------------------|
| `report.md`            | Full technical report in Markdown format      |
| `MrRobot_Report.pdf`   | Final version of the report in PDF            |
| `screenshots/`         | All supporting images used in the report      |
| `notes.txt`            | Raw commands and terminal outputs             |

---

## 🏁 Flags Captured

| Flag Number | Key Value                                |
|-------------|-------------------------------------------|
| Key 1       | `073403c8a58a1f80d943455fb30724b9`        |
| Key 2       | `822c2b3a50f3e92a0983edfa84815b6f`        |
| Root Flag   | `04787ddef27c3dee1ee161b21670b4e4`        |

---

## 📚 Learning Outcomes

- Gained experience in WordPress exploitation
- Improved directory enumeration and brute-force tactics
- Practiced realistic privilege escalation
- Understood how to document professional penetration test reports

---

## 📌 Report Link

👉 [Click here to view the full report](./report.md)

---

## 📸 Screenshots Preview

All screenshots are available in the `screenshots/` folder, named step-by-step to match the report timeline.

---

## ⚠️ Disclaimer

This machine is designed for **legal and educational** penetration testing practice only. Do not attempt any similar actions on unauthorized systems.

---
