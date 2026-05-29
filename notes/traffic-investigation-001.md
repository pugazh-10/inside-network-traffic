# Traffic Investigation 001

## Scenario

Captured network traffic while accessing:

- Google
- YouTube
- LinkedIn
- GitHub
- ChatGPT

## DNS Findings

### Observed Domains

- microsoft.com
- google.com
- gstatic.com
- youtube.com
- linkedin.com
- chatgpt.com
- github.com

### DNS Record Types

- A (IPv4)
- AAAA (IPv6)

### Additional Domain Investigation

Observed DNS requests to:

- gstatic.com

Analysis revealed that gstatic.com is commonly used by Google services to deliver static resources such as fonts, images, and JavaScript files.

## TCP Findings

Observed successful TCP three-way handshakes:

- SYN
- SYN ACK
- ACK

This confirmed successful connection establishment before data transmission.

## TLS Findings

Observed encrypted TLS traffic.

This indicates that communication between the client and server was protected using encryption.

## Key Learning

Modern web applications rely on multiple supporting domains and encrypted communication channels. DNS resolution, TCP connection establishment, and TLS encryption work together to enable secure web browsing.

## Analyst Perspective

Unexpected domains should not immediately be considered malicious. Analysts must investigate whether domains are legitimate service dependencies or indicators of suspicious activity.

## Conclusion

The investigation provided visibility into DNS activity, TCP session establishment, and encrypted web communication patterns during normal browsing behavior.
