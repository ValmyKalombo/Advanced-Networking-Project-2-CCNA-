# Advanced-Networking-Project-2-CCNA-
This repository contains the full implementation of a multi-branch enterprise network designed for Gijima Trading, including VLAN segmentation, DHCP centralisation, RIP v2 routing, WAN serial connections, wireless infrastructure, and QoS prioritisation for VoIP and conferencing traffic.

# ⭐ Project Overview

This project demonstrates:

Advanced IP addressing and subnetting

Centralised DHCP & DNS

Multi-site WAN connectivity with serial links

RIP v2 routing

VLAN segmentation & Inter-VLAN Routing

Wireless LAN Controller configuration

Wireless SSIDs & security

External Web Server integration

QoS for VoIP & video conferencing traffic

All configurations were built in Cisco Packet Tracer 8.2.2.

# ⭐ Features Implemented
✔ VLANs & Inter-VLAN Routing

Johannesburg: VLANs 10, 20, 30

Cape Town: VLANs 100, 200

Trunking & SVI routing enabled

✔ WAN Connectivity

Point-to-point leased lines

Serial DCE/DTE connections

Full routing with RIP v2

✔ DHCP & DNS

Centralised at Bloemfontein

All branches receive IPs through DHCP Relay (ip helper-address)

✔ Wireless LAN Controller

WLC Management IP: 192.168.20.3

SSIDs: STAFF-WIFI and GUEST-WIFI

WPA2 security for staff, open guest network with isolation

✔ Internet Cluster

External Web Server (200.20.20.10)

DNS A Record: www.traction.com

Reachable from all internal networks

✔ QoS for VoIP & Video

LLQ (Low Latency Queueing)

DSCP EF marking

CBWFQ for application prioritisation

# 📁 Project Files

.pkt – Complete Packet Tracer file

.docx – Full research report

/Screenshots/ – All configuration evidence

QoS_Question3 – QoS diagrams & explanation

# 🚀 How to Open the Project

Download or clone the repository

Open Advanced Networking Project 2.pkt using Cisco Packet Tracer 8.2.2 or later

Open the full report for explanation and documentation

# 🧪 Testing

RIP route propagation verified

DHCP leases tested across every branch

VLAN communication verified

WLC SSIDs reachable

Web server accessible at:

http://www.traction.com


QoS queues verified with show policy-map interface

# 📬 Author

Valmy Kalombo
Network & Security Engineering Student
LinkedIn: www.linkedin.com/in/valmy-kalombo-b606b7257
