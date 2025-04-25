# TryHackMe - HTTP Fundamentals

**Platform**: TryHackMe  
**Room**: [HTTP Fundamentals](https://tryhackme.com/room/http)  
**Category**: Networking / Protocols

---

## Overview

This room provided a beginner-friendly but comprehensive overview of how the HTTP protocol works. It covered HTTP request/response structure, status codes, headers, methods (GET, POST, PUT, etc.), and how web servers and clients communicate.

---

## Key Concepts Learned

- Structure of HTTP requests and responses
- Understanding status codes (200, 404, 403, 500, etc.)
- Common HTTP methods: GET, POST, PUT, DELETE
- Header fields like `User-Agent`, `Host`, and `Content-Type`
- How a browser sends HTTP requests and receives content
- How to inspect and analyze HTTP traffic using browser tools or `curl`

---

## Tools Used

- **Browser Developer Tools** (Network tab)
- **curl** – to manually send HTTP requests
- **Wireshark** – for capturing and analyzing HTTP packets

---

## Reflections

This room helped me better understand how web applications communicate and how requests are structured. It gave me insight into how attackers might exploit or manipulate HTTP traffic, which is a useful foundation for security monitoring and detection in a SOC environment.

---

## Next Steps

- Practice analyzing HTTP logs in SIEM
- Learn about HTTPS and TLS
- Explore HTTP header-based attacks (e.g., Host header injection)
