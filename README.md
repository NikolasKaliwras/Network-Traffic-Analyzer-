# Network Traffic Analyzer

> An all-in-one application for network security, monitoring, and management tailored for security experts, IT specialists, and administrators.

The Network Traffic Analyzer is a Windows-based solution that integrates Npcap with Scapy to enable Network Packet Capture (NPC). It applies protocol-specific algorithms to extract data, analyze for malicious activities, and display actionable intelligence through a real-time, user-friendly interactive dashboard.

---

## Key Features

* **Multi-Protocol Support:** Deep inspection of TCP, UDP, HTTP, DNS, ARP, and ICMP traffic.
* **Real-Time Monitoring:** Continuously updating graphs and charts for instant network visibility.
* **Top Talkers Identification:** Highlights the most active IP addresses and ports.
* **Automated Security Alerts:** Detects unauthorized activities like port scanning and strange DNS queries.
* **Advanced Filtering:** Customize data visualization by specific protocols, IPs, or ports.
* **Network Flow Analysis:** Tracks host-based connections similar to NetFlow/IPFIX.
* **Protocol Statistics:** Detailed bandwidth usage breakdown by protocol.

---

## Core Components

* **Packet Capture System:** Utilizes Scapy and Npcap with a multi-threaded processing model for efficient queue management.
* **Protocol Parsers:** Modular parsers that disassemble protocols and identify suspicious behaviors within specific protocol contexts.
* **Traffic Analysis Engine:** Measures bandwidth consumption and identifies usage trends or network choke points.
* **Security Analysis Engine:** Evaluates traffic for threats using multiple detection algorithms while minimizing false positives.
* **Anomaly Detection Module:** Uses statistical baselines to spot deviations and novel threats.
* **Interactive Dashboard:** Built with Plotly Dash and Bootstrap for live data visualization.
* **Reporting System:** Generates comprehensive, compliance-ready HTML reports.

---

## System Requirements

| Requirement | Specification |
| :--- | :--- |
| **Operating System** | Windows 10/11 (64-bit) |
| **Python** | Version 3.7+ (Python 3.9 recommended) |
| **Memory (RAM)** | Minimum 4GB (8GB recommended for larger networks) |
| **Storage** | 500MB base space, plus additional storage for packet captures |
| **Network Interface** | Active network interface with
