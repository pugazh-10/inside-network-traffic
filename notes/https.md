# HTTPS Analysis Notes

## What is HTTPS?

HTTPS (HyperText Transfer Protocol Secure) encrypts communication between clients and servers using TLS.

## Observation

While capturing HTTPS traffic, packet contents were encrypted and not readable in plain text.

## Key Findings

- HTTPS uses TLS encryption.
- Data remains protected during transmission.
- Packet metadata is visible, but content is encrypted.

## Security Relevance

HTTPS protects sensitive information from interception and helps ensure secure communication across networks.
