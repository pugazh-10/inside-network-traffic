# Inside Network Traffic

A hands-on cybersecurity learning repository documenting my journey into Network Traffic Analysis using Wireshark.

## Objective

The goal of this repository is to understand how cybersecurity analysts inspect network traffic, identify communication patterns, and investigate suspicious activity through packet analysis.

## Tools Used

- Wireshark
- Windows
- DNS Packet Analysis

## DNS Analysis

![DNS Analysis](screenshots/dns-analysis.png)

### Observation

While analyzing network traffic, I observed multiple DNS queries generated when accessing Google services.

### Key Findings

- DNS translates domain names into IP addresses.
- Every website visit generates DNS activity.
- DNS traffic provides visibility into communication patterns.
- Analysts frequently investigate DNS traffic during incident response.

### Security Relevance

DNS monitoring helps security analysts identify suspicious communication patterns, investigate incidents, and improve network visibility.

## Learning Journey

Next Topics:

- TCP Three-Way Handshake
- HTTP vs HTTPS
- Packet Filtering
- Wireshark Filters
- SOC Monitoring Concepts

Cybersecurity Learning Journey 🚀


## TCP Analysis

![TCP Analysis](screenshots/tcp-handshake.png)

### Observation

While analyzing network traffic, I observed TCP connections establishing communication through the three-way handshake process.

### Key Findings

- SYN initiates the connection.
- SYN-ACK acknowledges the request.
- ACK completes the handshake.
- TCP ensures reliable communication before data transfer begins.

### Security Relevance

Understanding TCP handshakes helps analysts identify abnormal network behavior, connection issues, and potential security threats.

## HTTP Analysis

![HTTP Analysis](screenshots/http-analysis.png)

### Observation

While analyzing HTTP traffic, requests and responses were visible in plain text.

### Key Findings

- HTTP communication is not encrypted.
- Web requests can be inspected directly.
- Sensitive information should not be transmitted over HTTP.

### Security Relevance

HTTP traffic can be intercepted and analyzed easily. This highlights the importance of HTTPS for secure communication.

## HTTPS Analysis

![HTTPS Analysis](screenshots/https-analysis.png)

### Observation

While analyzing HTTPS traffic, communication was encrypted using TLS.

### Key Findings

- HTTPS protects transmitted data.
- Packet contents are not visible in plain text.
- Encryption improves confidentiality and security.

### Security Relevance

HTTPS helps prevent eavesdropping, data theft, and tampering during communication.


## Investigations

- Traffic Investigation 001 – Network Traffic Fundamentals
- Traffic Investigation 002 – Domain Dependency Analysis
