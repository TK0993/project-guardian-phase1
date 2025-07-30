# Project Guardian Toolkit: Phase 1 – Home Network Defense

## 👨‍💻 Created by Tom Kemp – Entry-Level IT & Cybersecurity Learner

Welcome to **Project Guardian Toolkit: Phase 1**, a hands-on home network defense project I developed as part of my journey into the IT world. This marks my very first real-world security deployment — done entirely by myself with free, open-source tools.

### 📅 Timeline
- **Started learning IT:** 2 weeks ago (via the Google IT Support Certificate)
- **Started this project:** Yesterday

In just a short time, I’ve gone from zero cybersecurity knowledge to building and deploying a full set of layered defenses on my own home network using Ubuntu Linux.

---

## 🚀 Mission

To protect my personal and family devices by:
- Harden the firewall
- Monitor for brute-force attacks
- Detect new devices joining the network
- Run malware scans
- Audit the full system security
- Perform basic network reconnaissance

And finally: **turn this into a portfolio-worthy project to prove my real, working skills.**

---

## 🧰 Tools Installed & Configured

| Tool       | Purpose                                                                 |
|------------|-------------------------------------------------------------------------|
| **UFW**    | Host firewall to control incoming/outgoing traffic                      |
| **fail2ban** | Watches logs for brute-force attacks, especially SSH                  |
| **arp-scan** | Detects all devices on the local network                               |
| **ClamAV**   | Command-line antivirus scanner                                         |
| **ClamTK**   | GUI for ClamAV – makes scanning simple visually                       |
| **lynis**    | Performs an automated full system security audit                      |
| **nmap**     | Port scanner used for basic vulnerability analysis                    |

All tools are configured and tested. Full evidence captured in screenshots.

---

## 📁 Screenshot Folder Structure

Each tool has its own folder with labeled screenshots:

```
/guardian-toolkit/
├── ufw/
├── fail2ban/
├── arp-scan/
├── clamav/
├── clamtk/
├── lynis/
├── nmap/
└── guardian-core/
```

Each folder contains real terminal screenshots of:
- Install process
- Configuration commands
- Test runs and output
- Verifications (e.g., `sudo ufw status`, `lynis audit system`)

---

## 🧠 Learning Milestones

- **Linux terminal**: Learned to use `apt`, `nano`, `cron`, `systemctl`, and more
- **Cybersecurity basics**: Learned how firewalls, port scanning, log analysis, and AV work together
- **Project discipline**: Documented everything, organized files, wrote explanations — all in 1 day

This project proves that with curiosity, determination, and the right mindset, you can build real-world skills fast. And this is just **Phase 1**.

---

## ✅ Next Steps (Phase 2)

- Setup **Raspberry Pi Guardian Node** for 24/7 defense
- Add **Pi-hole** for ad blocking & DNS logging
- Add **Wireshark** or **Zeek** for deep packet inspection
- Expand monitoring into cloud backups and alerting

---

## 📢 Final Words

If you're an employer, mentor, or fellow learner: I hope this project shows what I’m capable of.

> 💬 *"I’ve only just begun, and I’m already building tools to protect my network and my family. Imagine what I’ll be doing in six months."*

Thanks for checking out my journey!

– **Tom Kemp** 🛡️
