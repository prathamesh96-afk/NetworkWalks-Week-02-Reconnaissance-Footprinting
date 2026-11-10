# NetworkWalks – Week 02
## Reconnaissance, Footprinting & Network Scanning

This repository contains my Week 02 practical work completed as part of the NetworkWalks Cybersecurity Training Program (Batch B084B).

The practical covers reconnaissance, footprinting, DNS information gathering, website technology identification and basic network scanning using Kali Linux and Zenmap.

---

## 📄 Project Report

- [View Recon Report (PDF)](Report/Recon%20Report.pdf)

---

## 📸 1. Reconnaissance & Footprinting Screenshots

The following tools were used for information gathering and reconnaissance activities.

| Sr. No. | Tool | Screenshot |
|---|---|---|
| 1 | WHOIS – Part 1 | [View Screenshot](Screenshots/whois%201.png) |
| 2 | WHOIS – Part 2 | [View Screenshot](Screenshots/whois%202.png) |
| 3 | cURL | [View Screenshot](Screenshots/curl.png) |
| 4 | DNSRecon | [View Screenshot](Screenshots/dns%20recon.png) |
| 5 | Nslookup | [View Screenshot](Screenshots/nslookup.png) |
| 6 | Wafw00f | [View Screenshot](Screenshots/wafw00f.png) |
| 7 | WhatWeb | [View Screenshot](Screenshots/whatweb.png) |

---

## 🌐 2. Network Scanning – Zenmap

Zenmap was used to perform network scanning and identify active hosts in the lab network.

**Scan Command:**

```bash
nmap -T4 -F 10.0.2.0/24
```

### Zenmap Scan Output

![Zenmap Scan Output](Screenshots/zenmap%201.png)

[View Zenmap Scan Screenshot](Screenshots/zenmap%201.png)

### Network Topology

![Zenmap Network Topology](Screenshots/zenmap%20topology.png)

[View Network Topology Screenshot](Screenshots/zenmap%20topology.png)

### Topology Report

[View Network Topology PDF](Evidence/Topology.pdf)

### Scan Summary

- **Target Network:** 10.0.2.0/24
- **Scanning Tool:** Zenmap / Nmap
- **Scan Profile:** Quick Scan
- **Active Hosts Discovered:** 3
- **Open Ports Observed:** 135, 139 and 445 on host 10.0.2.15

---

## 💻 3. Commands Used

The commands used during the practical are documented separately.

- [View Commands – commands.md](Commands/commands.md)

---

## 🎯 4. Learning Outcomes

- Understood basic reconnaissance and footprinting concepts.
- Practiced domain information gathering using WHOIS.
- Performed DNS enumeration using DNSRecon and Nslookup.
- Identified website technologies using WhatWeb.
- Checked HTTP response headers using cURL.
- Learned basic WAF detection using Wafw00f.
- Performed network scanning using Zenmap.
- Observed active hosts, open ports and network topology.

---

## ⚠️ Disclaimer

All activities were performed for educational purposes within the authorized practical scope. Network scanning and security testing should only be conducted on systems for which proper permission has been granted.

---

## 👨‍💻 Author

**Name:** Prathamesh Kisan Satre  
**Program:** NetworkWalks Cybersecurity Training  
**Batch:** B084B  
**Practical:** Week 02 – Reconnaissance, Footprinting & Network Scanning
