
# MyRoomWiFi – Home Network Simulation (Cisco Packet Tracer)

This project simulates a realistic my home WiFi network using Cisco Packet Tracer, demonstrating wireless and wired device connectivity, DHCP configuration, and simulated internet access.

---

## Network Overview

- **SSID:** `MyRoomWiFi`
- **Security:** WPA2-PSK (AES Encryption)
- **WiFi Channel:** 6 (2.4 GHz)
- **WiFi Range:** 250 meters
- **Authentication Passphrase:** `mypassword`

---

## 🧱 Devices Used

- Wireless Router
- Multiple PCs (wired)
- Smartphones (wireless)
- Optional: Cloud + DSL Modem (for internet simulation)

---

## 🌐 Network Configuration

| Parameter       | Value                    |
|---------------- |--------------------------|
| **Router IP**   | `192.168.1.1`            |
| **Subnet Mask** | `255.255.255.0`          |
| **DHCP Enabled**| Yes                      |
| **DHCP Range**  | `192.168.1.100 - 192.168.1.149` |
| **DNS Server**  | `8.8.8.8` (configurable manually) |

---

## 🔌 Device Configuration Example

### PC (Wired)
- IP via DHCP (e.g., `192.168.1.10`)
- Subnet: `255.255.255.0`
- Gateway: `192.168.1.1`

### Smartphones (WiFi)
- Connect using SSID `MyRoomWiFi`
- Enter passphrase `mypassword`
- Receive dynamic IP from DHCP

---

## ✅ Features

- All devices successfully connect via wireless or wired interfaces
- DHCP server assigns IPs dynamically
- Secure WiFi communication with WPA2
- Optional internet simulation using cloud & DSL modem
- Ideal for learning **basic home networking** principles

## 📁 Files Included

- `My_Wifi_Network.pkt` – Packet Tracer project file


## 📌 Purpose

This project is created for educational purposes to help learners understand:

- Home router configuration
- Wireless security (WPA2 setup)
- DHCP-based dynamic IP assignment
- Basic LAN communication

---
Created by: Abhishek Yadav  


