# HTTP Analysis Notes

## What is HTTP?

HTTP (HyperText Transfer Protocol) is used to transfer web content between clients and servers.

## Observation

While capturing traffic in Wireshark, HTTP requests and responses were visible in plain text.

## Key Findings

- HTTP traffic is not encrypted.
- Requests and responses can be viewed directly.
- Data transmitted through HTTP can be intercepted.

## Security Relevance

HTTP lacks encryption, making it vulnerable to eavesdropping and man-in-the-middle attacks. Modern websites use HTTPS to secure communication.
