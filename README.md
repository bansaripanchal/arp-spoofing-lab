# 🔐 ARP Spoofing Lab (Ethical Hacking)

## 📌 Objective

To understand how ARP Spoofing (MITM attack) works in a controlled lab environment using Kali Linux and Windows.

---

## 🛠️ Tools Used

* Kali Linux
* Windows 7 (VM)
* Ettercap
* Wireshark

---

## 🌐 Lab Setup

* Both machines connected using **Host-Only Network**
* Same IP range (e.g., 192.168.x.x)

---

## ⚙️ Steps Performed

1. Configured network (Host-only adapter)
2. Verified connectivity using ping
3. Opened Ettercap and enabled sniffing
4. Scanned for hosts
5. Selected targets (Windows + Gateway)
6. Performed ARP poisoning
7. Captured traffic using Wireshark
8. Filtered HTTP traffic

---

## 📊 Result

* Successfully captured HTTP traffic
* Observed network packets using Wireshark
* Understood limitation of HTTPS (encrypted traffic)

---

## 🚀 Learning Outcome

* Networking basics (IP, ARP)
* MITM attack concept
* Packet analysis using Wireshark

