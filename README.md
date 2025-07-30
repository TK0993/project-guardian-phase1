
# 🛡️ Project Guardian Toolkit: Phase 1 – Home Network Defense

## 🚀 Mission Statement

Project Guardian Toolkit is a personal cybersecurity initiative by **Thomas Andrew Kemp** to harden and monitor a home network using free, open-source tools. This project is designed to protect all connected devices—PCs, phones, laptops, smart TVs, and more—against common threats such as port scanning, brute-force attacks, viruses, and unauthorized device access.

🔰 **This toolkit was developed by someone who started their IT learning journey just 2 weeks ago, with no prior experience.**  
It’s proof that you don’t need years of experience to start building real-world cybersecurity tools. If you're learning IT or security, this project is for you!

---

## 🧰 Tools Installed and Configured

| Tool       | Status       | Description |
|------------|--------------|-------------|
| **ufw**    | ✅ Installed | Simple firewall manager for iptables – default deny, only allow specific ports |
| **fail2ban** | ✅ Installed & running | Monitors log files for repeated failed login attempts and bans IPs |
| **arp-scan** | ✅ Installed | Scans local network to detect all connected devices (useful for unknown connections) |
| **clamav + clamtk** | ✅ Installed | Antivirus engine (CLI + GUI), used to scan the system for viruses/malware |
| **lynis**  | ✅ Installed & scanned | Deep Linux security audit tool – flags configuration issues and vulnerabilities |
| **nmap**   | ✅ Installed | Advanced network scanner – maps open ports, OS versions, running services |

---

## 📂 Folder and Screenshot Structure

To keep everything organized, each tool has its **own folder** inside the project directory. Each folder contains:

- 📸 Screenshot(s) of the tool in use
- 📝 Any logs or output (if saved)
- 🔧 Notes on how to install or configure the tool

**Example structure:**

```
GuardianToolkit/
├── ufw/
│   └── screenshot-ufw-rules.png
├── fail2ban/
│   └── screenshot-fail2ban-status.png
├── arp-scan/
│   └── screenshot-device-scan.png
├── clamtk/
│   └── screenshot-virus-scan.png
├── lynis/
│   └── screenshot-lynis-audit.png
├── nmap/
│   └── screenshot-port-scan.png
```

---

## 🧠 My Learning Timeline

| Date Started | Milestone |
|--------------|-----------|
| 2 weeks ago  | Began Google IT Support course |
| Day 1        | Learned about Linux terminal and dual-booting |
| Day 2–7      | Installed tools, began configuring firewall and security scanners |
| Day 8–14     | Completed Guardian Toolkit Phase 1, documented project, created GitHub README |

---

## 🙌 Credits & Motivation

Created by **Thomas Andrew Kemp** – an aspiring IT Support and Cybersecurity Specialist.  
Father of two amazing girls, building a better and safer future through tech.  
This is only **Phase 1** – more to come in **Phase 2**, including intrusion detection, log monitoring, and automated alerts.

---

## 📌 Coming Soon: Phase 2 – Advanced Network Monitoring

Stay tuned for:
- `arpwatch` for real-time MAC/IP changes  
- `logwatch` for daily summaries  
- `pi-hole` for DNS-based ad & tracking blocking  
- `Wireshark` packet captures and analysis  
- Raspberry Pi Guardian Node version

---

> ✨ *“I started with nothing but curiosity and a goal to protect my home network. If I can do it, so can you.”*
