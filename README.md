# Router and Switch Configuration using Cisco Packet Tracer

## 📌 Project Description
This project demonstrates the configuration of a router and switches using Cisco Packet Tracer. The goal is to enable communication between two different LAN networks by assigning IP addresses and configuring router interfaces.

The project helps in understanding basic networking concepts used in real-world IT infrastructures.

---

## 🛠 Tools Used
- Cisco Packet Tracer

---

## 🌐 Network Topology

Devices used in the network:

- 1 Router (Cisco 1841)
- 2 Switches (Cisco 2960)
- 4 PCs

Two LAN networks are connected through a router.

Network 1: **192.168.1.0 /24**  
Network 2: **192.168.2.0 /24**

---

## 💻 IP Address Configuration

| Device | IP Address | Subnet Mask | Default Gateway |
|------|------|------|------|
| PC0 | 192.168.1.102 | 255.255.255.0 | 192.168.1.101 |
| PC1 | 192.168.1.103 | 255.255.255.0 | 192.168.1.101 |
| PC2 | 192.168.2.102 | 255.255.255.0 | 192.168.2.101 |
| PC3 | 192.168.2.103 | 255.255.255.0 | 192.168.2.101 |

---

## ⚙ Router Configuration

Router interfaces were configured to connect two networks.

FastEthernet0/0 → Network **192.168.1.0**  
FastEthernet0/1 → Network **192.168.2.0**

---

## 🔧 Switch Configuration

Switches are used to connect multiple devices within each LAN network.

Basic configuration was performed including assigning hostnames.

---

## 🧪 Network Testing

Network connectivity was verified using the **ping command**.

```bash
ping 192.168.2.102
ping 192.168.1.102

These skills are essential for understanding real-world networking environments.
