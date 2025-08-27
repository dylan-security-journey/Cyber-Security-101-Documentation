# Networking Protocols, Models, and Tools

---

## 1. OSI & TCP/IP Models

### OSI Model (7 Layers)
1. **Physical** – wires, physical connection.  
2. **Data Link** – transfer on same network (Ethernet, Wi-Fi).  
3. **Network** – logical addressing, routing (IP).  
4. **Transport** – reliability, ports (TCP/UDP).  
5. **Session** – establishes sessions between systems.  
6. **Presentation** – formatting, encryption.  
7. **Application** – user-facing applications (HTTP, FTP, SMTP).  

![OSI Model](https://github.com/user-attachments/assets/3ea70f86-f563-480c-b870-cc7101f53434)

### TCP/IP Model (5 Layers)
1. Physical  
2. Data Link  
3. Network  
4. Transport  
5. Application  

![TCP/IP](https://github.com/user-attachments/assets/8886eed0-2800-4b94-afb5-66cf0fbcbf97)

---

## 2. TCP vs UDP

- **TCP**  
  - Connection-oriented, requires confirmation.  
  - Data unit = **Segment**.  
- **UDP**  
  - Connectionless, no confirmation.  
  - Data unit = **Datagram**.  
- Both use **Layer 4 (Transport Layer)**.  
- Up to **65K ports** available.  

![TCP vs UDP](https://github.com/user-attachments/assets/155861b7-4cb2-44f8-8fc1-e58a6b04df6f)

---

## 3. Networking Functions

- **Ethernet & Wi-Fi** → Major Layer 2 functions.  
- **ARP (Address Resolution Protocol)** → Translates IP (Layer 3) to MAC (Layer 2).  
- **TTL (Time to Live)** → Field in IP packet decrements to 0 → “time exceeded” message.  
- **NAT (Network Address Translation)** → Maps private IPs to public IPs for internet communication.  

![NAT Example](https://github.com/user-attachments/assets/b762b545-e2b7-4fea-ad20-c8fbc60a6e13)

---

## 4. Telnet & FTP

### Telnet
- Used for connecting to servers over **TCP**.  
- Case-sensitive commands.  
- Data is in **cleartext** → insecure.  

![Telnet Example](https://github.com/user-attachments/assets/f12c9ec8-3345-4c19-839a-1690d864c3b8)

### FTP (File Transfer Protocol)
- Retrieves and sends files.  
- Uses cleartext → insecure.  
- Secure alternative: **FTPS / SFTP**.  

![FTP Example](https://github.com/user-attachments/assets/7f68087d-8567-4096-bb73-27014d461414)

---

## 5. DNS & Domains

- `whois` → Retrieve domain registration info.  
- **AAAA Record** → IPv6 address.  
- DNS resolves **domain → IP address**.  

![WHOIS](https://github.com/user-attachments/assets/0bc4a8b3-23b0-4d38-8b21-e8cbcb3b2fb0)

---

## 6. Email Protocols

- **IMAP** (143) → Unencrypted.  
- **IMAPS** (993) → Secure version.  
- **SMTP/POP3** also have secure equivalents.  
- Dovecot shown in server example.  

![Email Server](https://github.com/user-attachments/assets/d9554f4d-2545-4154-b651-4f2e2aa490f9)

---

## 7. TLS & Secure Communication

- **TLS (Transport Layer Security)** built upon SSL.  
- Provides **encryption** for HTTP → HTTPS.  
- Self-signed certificates = not trusted.  
- Protocols add **“S”** when secure (HTTPS, IMAPS, SMTPS).  
- Example: IMAP (143) vs IMAPS (993).  
- **Telnet** is insecure → use **SSH (OpenSSH, port 22)**.  

![TLS Handshake](https://github.com/user-attachments/assets/5922c664-2a97-429d-8a47-2c416accff89)

---

## 8. Packet Analysis (Wireshark)

- Tool to **inspect packets** (not modify).  
- Features:  
  - Coloring rules.  
  - Exporting & merging capture files.  
  - Packet navigation & search.  
  - Capture comments for history.  
- OSI breakdown visible in Wireshark (TTL in Layer 3, Payload in TCP).  

![Wireshark Example](https://github.com/user-attachments/assets/6cf21063-32b0-463d-b514-5ac23998518e)

---

## 9. tcpdump

- CLI packet capture tool.  
- Library: **libpcap**.  
- Options:  
  - `-n` → show numeric IP instead of DNS.  
  - `-w` → write to file (pcap).  
  - `wc` → count packets.  

![tcpdump Example](https://github.com/user-attachments/assets/3336a2fb-4914-47eb-926a-0d289e8b074a)

---

## 10. Nmap (Network Mapper)

- Used for scanning hosts and ports.  
- Common options:  
  - `-sn` → Host discovery (which hosts are up).  
  - `-sL` → List scan (IP list only).  
  - `-sV` → Detect version of services.  
  - `-p` → Specify ports.  

![Nmap Example](https://github.com/user-attachments/assets/e79b4b2d-44e3-43d4-926f-8d2238342f08)

---

## 11. Key Takeaways
- OSI = 7 layers (theoretical), TCP/IP = 5 layers (practical).  
- TCP vs UDP = Reliability vs Speed.  
- NAT, TTL, and ARP critical for networking.  
- Insecure protocols: **Telnet, FTP, IMAP** → replace with secure versions.  
- TLS = encryption standard, HTTPS and SSH are secure defaults.  
- **Wireshark & tcpdump** are essential packet analysis tools.  
- **Nmap** = gold standard for network discovery and port scanning.  





















