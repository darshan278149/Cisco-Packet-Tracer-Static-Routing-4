# Cisco Packet Tracer - 4 Router Static Routing Lab

## 📖 Overview

This project demonstrates the implementation of Static Routing using four Cisco routers in Cisco Packet Tracer. Each router is connected to its own LAN through a switch, allowing communication between all networks using manually configured static routes.

The project focuses on understanding IP addressing, static routing, routing tables, and troubleshooting network connectivity.

---

## 🎯 Objectives

- Configure IP addresses on routers and PCs.
- Configure static routes on all routers.
- Establish communication between four different LANs.
- Verify routing using Cisco IOS commands.
- Test end-to-end connectivity using ping.

---

## 🛠 Technologies Used

- Cisco Packet Tracer
- Cisco IOS CLI
- Static Routing
- IPv4 Addressing

---

## 🖥 Network Devices

- 4 Cisco Routers
- 4 Cisco Switches
- 8 PCs

---

## 🌐 Network Topology

```
LAN A ----- Router A ----- Router B ----- Router C ----- Router D ----- LAN D
```

---

## 📍 IP Addressing

### LAN Networks

| Router | Gateway | Network |
|---------|----------|---------|
| Router A | 192.168.1.1 | 192.168.1.0/24 |
| Router B | 12.0.0.1 | 12.0.0.0/8 |
| Router C | 15.0.0.1 | 15.0.0.0/8 |
| Router D | 18.0.0.1 | 18.0.0.0/8 |

### Serial Links

| Connection | IP Address |
|------------|------------|
| Router A ↔ Router B | 10.0.0.1 / 10.0.0.2 |
| Router B ↔ Router C | 172.147.1.1 / 172.147.1.2 |
| Router C ↔ Router D | 155.123.1.1 / 155.123.1.2 |

---

## ⚙ Configuration Steps

- Assigned IP addresses to all router interfaces.
- Configured IP addresses and default gateways on all PCs.
- Enabled interfaces using `no shutdown`.
- Configured static routes using the `ip route` command.
- Verified routing tables using `show ip route`.
- Tested connectivity using the `ping` command.

---

## 📋 Cisco IOS Commands Used

```
enable
configure terminal
ip address
no shutdown
ip route
show ip route
show ip interface brief
ping
```

---

## ✅ Results

- Successfully configured static routing across four routers.
- Achieved end-to-end communication between all LANs.
- Verified successful packet transmission using ping.
- Practiced troubleshooting routing issues by correcting missing and incorrect static routes.

---

## 🎓 Skills Learned

- IPv4 Addressing
- Static Routing
- Router Configuration
- Cisco IOS CLI
- Routing Table Analysis
- Network Troubleshooting
- End-to-End Connectivity Testing

---

## 📷 Screenshots

- Network Topology
- Router Configurations
- Routing Tables
- Successful Ping Results

---

## 📄 Project Purpose

This project was created to strengthen networking fundamentals and gain hands-on experience with Cisco routers, static routing, and troubleshooting using Cisco Packet Tracer.

---

## 👨‍💻 Author

**Darshan Ramesh Ratnapalke**

GitHub: https://github.com/darshan278149
