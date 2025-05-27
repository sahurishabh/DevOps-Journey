# 🌐 Networking Concepts for DevOps & Cloud Engineers

Welcome to this repository of foundational **networking concepts** — essential for anyone pursuing a DevOps, Cloud, or Systems Engineering journey. This guide covers key protocols, models, and tools modern networks use.

---

## 📶 OSI Model vs. TCP/IP Model

### 🧱 OSI Model (Open Systems Interconnection)

The OSI model is a conceptual framework that helps us understand how different networking protocols work together. It breaks the communication process into 7 layers, from sending data physically to interacting with applications.

**OSI Layers:**
1. **Physical**     – Hardware and raw bit transmission (e.g., cables, switches)
2. **Data Link**    – Node-to-node communication, MAC addressing
3. **Network**      – Routing and IP addressing (e.g., routers)
4. **Transport**    – Reliable delivery (e.g., TCP, UDP)
5. **Session**      – Session management and dialog control
6. **Presentation** – Data translation, encryption, compression
7. **Application**  – End-user interaction (e.g., HTTP, FTP)

---

### 🌐 TCP/IP Model (Transmission Control Protocol)

It is a set of communication protocols used to connect network devices on the Internet.
TCP/IP is also used for communication within private networks, such as intranets or extranets.

**TCP/IP Layers:**
1. **Network Access** – Physical + Data Link
2. **Internet**       – IP addressing and routing
3. **Transport**      – TCP/UDP for end-to-end communication
4. **Application**    – HTTP, FTP, DNS, etc.

---

### 🔁 OSI vs TCP/IP Comparison

| OSI Model    | TCP/IP Model   |
| ------------ | -------------- |
| Application  | Application    |
| Presentation | Application    |
| Session      | Application    |
| Transport    | Transport      |
| Network      | Internet       |
| Data Link    | Network Access |
| Physical     | Network Access |

---

## 🚀 Key Networking Terms

### 🔸 UDP (User Datagram Protocol)
- A **Transport Layer protocol**
- Used in **video streaming, gaming, and VoIP (Voice Over Internet Protocol)**
- Faster but less reliable (no error checking)
- Supports multicast (sending to multiple recipients)

---

### 🔸 FTP (File Transfer Protocol)
- Used for **transferring files between a client and server**
- Example client: **FileZilla**
- Works over **TCP**, typically on ports 20/21

---

### 🔸 CIDR (Classless Inter-Domain Routing)
- IP addressing method for **allocating and routing** IP addresses efficiently
- Allows flexible subnetting beyond traditional class-based IPs

---

### 🔸 DNS (Domain Name System)
- Converts **domain names (e.g., www.google.com)** into **IP addresses (e.g., 192.168 1.1)**
- Acts like the internet's phonebook

---

### 🔸 SSH (Secure Shell/Secure Socket Shell)
- Enables **secure remote login and file transfer**
- Uses **encryption** for secure communication
- Default port: **22**

---

### 🔸 Subnet
- A **smaller network** within a larger network
- Helps isolate sections for better **security** and **management**
- Example: Splitting a 192.168.0.0/16 into smaller /24 networks

---

### 🔸 Switch
- A device that **connects multiple devices** in a LAN
- Operates at **Layer 2 (Data Link)** of the OSI model
- Uses **MAC addresses** to forward data

---

### 🔸 Router
- Connects **different networks**
- Operates at **Layer 3 (Network)** of the OSI model
- Forwards data based on **IP addresses**

---


