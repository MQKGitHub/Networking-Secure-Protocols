## 🛡️ Networking Secure Protocols

**Room:** [Networking Secure Protocols — TryHackMe](https://tryhackme.com/room/networkingsecureprotocols)  
**Status:** ✅ Completed  
**Date:** *21 May 2025* 

### 🎯 Objective
This room focused on securing network communications through TLS/SSL, SSH, and VPN technologies. The goal was to understand how these protocols protect data confidentiality, integrity, and authenticity when using common services like web browsing, email, and remote access.

---

### 🗝️ Key Concepts  
- **TLS/SSL** — Cryptographic protocols providing confidentiality, integrity, and authenticity for network communications  
- **Protocol Security Upgrades** — How plaintext protocols (HTTP, SMTP, etc.) become secure (HTTPS, SMTPS, etc.)  
- **Certificate Authorities** — Trusted entities that validate and sign digital certificates  
- **SSH** — Secure replacement for TELNET offering encrypted remote access and file transfer  
- **VPN Technologies** — Creating secure private networks over public internet infrastructure  
- **Encrypted File Transfer** — Differences between SFTP (SSH-based) and FTPS (TLS-based)  
- **Traffic Analysis** — Using Wireshark with decryption keys to inspect secure protocols  
- **Port Security** — Default secure protocol ports (HTTPS:443, SSH:22, IMAPS:993, etc.)  

---

### 🛠️ Tools Used  
- **Wireshark** — For analyzing encrypted traffic (with TLS decryption keys)  
- **OpenSSH** — For secure remote access and file transfers  
- **Chromium (with SSL logging)** — For capturing TLS session keys  
- **VPN clients** — For testing secure tunnel connections  

---

### ⚠️ Challenges Faced  
- Understanding the differences between similar protocols (SFTP vs FTPS)  
- Visualizing how VPN tunneling actually works at the packet level

---

### 🧠 What I Learned  
- How TLS transforms insecure protocols into secure versions (HTTP→HTTPS, etc.)  
- The complete process from CSR generation to certificate installation  
- Why SSH is considered more secure than TELNET (encryption, authentication methods)  
- How VPNs can make geographically separate networks appear as one private network  

---

### 🌐 Real-World Application:
> These protocols form the backbone of secure communications:
> - TLS secures all sensitive web transactions (banking, healthcare, etc.)
> - SSH is essential for secure server administration
> - VPNs enable secure remote work and bypass geographical restrictions
> - Understanding these helps troubleshoot security issues and implement proper protections

---

### 💭 Reflections:
- **Most Valuable:** Hands-on Wireshark decryption showed exactly what TLS protects
- **Surprising:** How easy it is to set up basic VPN connections
- **Unforgettable:** That you can intercept "secure" traffic if you have the private keys!
