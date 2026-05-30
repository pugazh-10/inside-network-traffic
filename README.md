# 🔍 Inside Network Traffic

> A hands-on Network Traffic Analysis project using Wireshark to investigate DNS, TCP, HTTP, HTTPS, and real-world communication patterns.

---

## 📌 Project Overview

This repository documents my practical journey into Network Traffic Analysis using Wireshark.

The goal is to understand how cybersecurity analysts inspect packet captures, identify communication patterns, investigate protocols, and analyze network behavior.

---

## 🎯 Objectives

- Understand packet-level communication
- Analyze DNS traffic
- Investigate TCP connections
- Examine HTTP and HTTPS sessions
- Learn packet filtering techniques
- Develop network investigation skills used in SOC environments

---

## 🛠️ Tools Used

| Tool | Purpose |
|--------|----------|
| Wireshark | Packet Capture & Analysis |
| Windows | Analysis Environment |
| DNS | Name Resolution Analysis |
| TCP | Transport Analysis |
| HTTP | Web Traffic Analysis |
| HTTPS | Secure Communication Analysis |

---

# 📂 Investigation Index

| Investigation | Description |
|--------------|-------------|
| Investigation 001 | DNS Traffic Analysis |
| Investigation 002 | TCP Session Analysis |
| Investigation 003 | HTTP Traffic Analysis |
| Investigation 004 | HTTPS Traffic Analysis |

---

# 🌐 Investigation 001 – DNS Traffic Analysis

## Objective

Understand domain name resolution and DNS packet structure.

## Activities Performed

- Captured DNS requests
- Observed DNS responses
- Identified queried domains
- Examined packet details

## Screenshot

![DNS Analysis](screenshots/dns-analysis.png)

## Findings

- DNS converts domain names into IP addresses.
- Multiple DNS queries are generated during website access.
- Query and response packets can be easily identified in Wireshark.

---

# 🔗 Investigation 002 – TCP Session Analysis

## Objective

Analyze TCP communication and session establishment.

## Activities Performed

- Inspected TCP packets
- Observed source and destination ports
- Analyzed session behavior

## Screenshot

![TCP Analysis](screenshots/tcp-analysis.png)

## Findings

- TCP provides reliable communication.
- Sessions contain source and destination endpoints.
- Packet flow can be tracked throughout the connection.

---

# 🌍 Investigation 003 – HTTP Traffic Analysis

## Objective

Inspect unencrypted web traffic.

## Activities Performed

- Captured HTTP packets
- Identified requests and responses
- Analyzed web communication flow

## Screenshot

![HTTP Analysis](screenshots/http-analysis.png)

## Findings

- HTTP data is visible in plaintext.
- Requests and responses can be inspected directly.
- Useful for understanding web communication mechanisms.

---

# 🔒 Investigation 004 – HTTPS Traffic Analysis

## Objective

Analyze encrypted web communications.

## Activities Performed

- Captured HTTPS packets
- Observed TLS handshakes
- Examined encrypted traffic behavior

## Screenshot

![HTTPS Analysis](screenshots/https-analysis.png)

## Findings

- HTTPS encrypts application data.
- TLS handshakes establish secure communication.
- Packet metadata remains visible while payloads stay encrypted.

---

# 📊 Protocols Observed

| Protocol | Purpose |
|----------|---------|
| DNS | Domain Resolution |
| TCP | Reliable Transport |
| HTTP | Web Communication |
| HTTPS | Secure Web Communication |
| TLS | Encryption Layer |

---

# 🔐 Cybersecurity Relevance

Network Traffic Analysis is a fundamental skill for:

- SOC Analysts
- Security Analysts
- Incident Responders
- Threat Hunters
- Blue Team Engineers

Traffic inspection helps identify:

- Malicious communications
- DNS anomalies
- Reconnaissance activity
- Suspicious connections
- Potential threat indicators

---

# 🚀 Phase 2 Roadmap

Planned enhancements:

- Suspicious Traffic Detection
- Port Scan Detection
- Alert Generation
- Threat Classification
- Packet Analytics Dashboard
- Security Event Logging

---

# 📚 Learning Outcomes

Through this project I learned:

- Packet capture techniques
- Protocol identification
- DNS investigation workflow
- TCP communication analysis
- HTTP/HTTPS traffic inspection
- Network investigation methodology

---

# 👨‍💻 Author

### Pugazhenthi Amulraj

Cybersecurity Student | SOC Analyst in Training | Network Security | SIEM | Linux

GitHub:
https://github.com/pugazh-10

LinkedIn:
https://www.linkedin.com/in/pugazhenthi-amulraj

---

⭐ If you found this repository useful, consider giving it a star.
