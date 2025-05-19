
**Secufi** is a low-cost, open-source network segmentation and monitoring solution designed to protect internal systems from guest users on shared public Wi-Fi. Built using OpenWrt, VLANs, Nodogsplash, and Snort, it offers practical cybersecurity for small businesses, educational institutions, and local public organizations in India.

---

## 🔍 Problem

Many small-scale establishments like cafes, clinics, and shops offer free Wi-Fi to customers using the same infrastructure that supports sensitive internal systems (billing, CCTV, POS, etc.). This lack of network segmentation exposes critical systems to threats like malware, sniffing, or unauthorized access.

---

## ✅ Solution Overview

Secufi isolates guest traffic from internal systems using VLAN-based segmentation on OpenWrt routers, while providing monitored and accountable internet access through captive portals and IDS monitoring.

---

## 🧩 Features

- 🔀 **VLAN-Based Network Segmentation**  
  Isolates guest and internal devices using OpenWrt and managed switches.

- 🌐 **Captive Portal Access (Nodogsplash)**  
  Forces guest users to accept terms or authenticate before gaining internet access.

- 🧱 **Firewall Rules & Routing Isolation**  
  Prevents any cross-talk between the guest and internal networks.

- 🕵️ **Intrusion Detection with Snort**  
  Real-time monitoring and alerting of suspicious network activities.

- 🧪 **GNS3 Simulated Testing Environment**  
  All configurations are tested in a virtual lab to validate attack scenarios and defenses.

---

## 🛠️ Tools & Technologies

| Tool         | Purpose                             |
|--------------|-------------------------------------|
| OpenWrt      | Custom router firmware              |
| VLANs        | Network segmentation                |
| Nodogsplash  | Captive portal for guest login      |
| Snort        | Intrusion detection and logging     |
| GNS3         | Network simulation and testing      |
| iptables     | Firewall and routing configuration  |

---

## 🧰 Folder Structure
secufi/
├── configs/ 
├── setup/ 
├── simulation/ 
├── images/ 
├── LICENSE
└── README.md


---

## 🚀 Getting Started

1. **Flash OpenWrt** on a compatible router  
2. **Configure VLANs** for internal and guest networks  
3. **Set up captive portal** with Nodogsplash  
4. **Deploy Snort** on the router or an attached device  
5. **Test the system** using simulated attacks in GNS3

➡️ Full step-by-step guides available in the `/setup` folder.

---

## 🧪 Simulation Preview

- ✅ Man-in-the-middle attacks blocked
- ✅ Guest-to-internal lateral movement prevented
- ✅ Unauthorized access attempts logged by Snort

> Demo screenshots and logs are available in the `/images` and `/simulation` folders.

---

## 🎯 Use Cases

- Coffee shops, clinics, coaching centers
- Schools and colleges with shared Wi-Fi
- Any public-facing organization with limited IT budgets


---

## 🙋 Contribute

Pull requests are welcome! If you have suggestions for improving Secufi or want to add support for more IDS systems, feel free to open an issue or fork the project.

---

## 🧠 Author

**Nandu A Lal**  
Cybersecurity & AI Enthusiast | India 🇮🇳  
Connect on [LinkedIn](https://www.linkedin.com/in/nandu-a-lal-a01693249/) or contribute right here!

---

