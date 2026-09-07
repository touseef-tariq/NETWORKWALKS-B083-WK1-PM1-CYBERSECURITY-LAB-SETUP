# NETWORKWALKS-B083-WK1-PM1-CYBERSECURITY-LAB-SETUP
# 🛡️ VirtualBox & Kali Linux Lab Setup

This repository contains my **Week 1 Cybersecurity Lab (WK1-PM1)** project. The objective was to configure a Kali Linux virtual machine using Oracle VirtualBox and prepare a basic penetration testing environment.

---

# 📋 Project Objectives

- Install Oracle VirtualBox
- Import Kali Linux Virtual Machine
- Create a NAT Network (10.0.0.0/24)
- Configure the Kali Linux network adapter
- Assign a static IP address (10.0.0.2)
- Enable Shared Clipboard and Drag-and-Drop
- Verify Internet connectivity
- Create a Virtual Machine Snapshot

---

# 💻 Software Used

| Software | Version |
|----------|----------|
| Oracle VirtualBox | 7.x |
| Kali Linux | 2026.2 |
| Host OS | Windows 10 |

---

# 🌐 Network Configuration

| Setting | Value |
|----------|-------|
| Network Type | NAT Network |
| Network Address | 10.0.0.0/24 |
| Kali IP Address | 10.0.0.2 |
| Gateway | 10.0.0.1 |
| Internet Access | Enabled |

---

#  Setup Process

## Step 1 – Create NAT Network

A NAT Network was created in VirtualBox using the following settings:

- Network Name: NatNetwork1
- IPv4 Prefix: 10.0.0.0/24
- DHCP: Enabled

![NAT Network](1-screenshot-nat-network.png)

---

## Step 2 – Configure Kali Linux Network Adapter

The Kali Linux virtual machine was connected to the NAT Network.

- Adapter 1: Enabled
- Attached To: NAT Network
- Name: NatNetwork1

![Network Adapter](2-screenshot-network-adapter.png)

---

## Step 3 – Enable Shared Clipboard & Drag-and-Drop

The following settings were enabled:

- Shared Clipboard: Bidirectional
- Drag-and-Drop: Bidirectional

![Clipboard Settings](3-screenshot-clipboard-settings.png)

---

## Step 4 – Configure Static IP Address

The IPv4 settings inside Kali Linux were configured as follows:

| Parameter | Value |
|-----------|-------|
| IP Address | 10.0.0.2 |
| Prefix | 24 |
| Gateway | 10.0.0.1 |

![IP Configuration](4-screenshot-ip-configuration.png)

---

## Step 5 – Verify Internet Connectivity

Internet access was verified by executing the following command:

```bash
ping google.com
```

The system successfully received replies from Google's servers, confirming that the virtual machine had Internet connectivity.

![Internet Test](5-screenshot-internet-test.png)

---

# Step 6 – Create Virtual Machine Snapshot

A VirtualBox snapshot was created after completing the lab configuration to preserve the working state of the virtual machine.

![VM Snapshot](6-screenshot-vm-snapshot.png)

---
# Learning Outcomes

This lab helped me gain practical experience with:

- Oracle VirtualBox
- Virtual Machine Management
- NAT Network Configuration
- Static IPv4 Configuration
- Linux Networking
- Internet Connectivity Testing
- Virtual Machine Snapshots

---

# 📂 Repository Contents

```text
README.md
1-screenshot-nat-network.png
2-screenshot-network-adapter.png
3-screenshot-clipboard-settings.png
4-screenshot-ip-configuration.png
5-screenshot-internet-test.png
6-screenshot-vm-snapshot.png
```

---

# ✅ Conclusion

The cybersecurity lab environment was successfully configured according to the project requirements. Kali Linux was connected to the NAT Network, assigned a static IP address, Internet connectivity was verified, and a VirtualBox snapshot was created for future use.

---

## 👤 Author

Touseef Tariq

Cybersecurity Student

# Project Information
Program Name: Cybersecurity at Networkwalks | Week: 01 | Project: Cybersecurity & Pentesting Lab Setup | Repository: GitHub

           
