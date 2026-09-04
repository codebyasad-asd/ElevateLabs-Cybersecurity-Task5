# 🦈 Task 5 — Capture and Analyze Network Traffic Using Wireshark

![Cybersecurity](https://img.shields.io/badge/Internship-Cybersecurity-blue)
![Tool](https://img.shields.io/badge/Tool-Wireshark-lightblue)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Overview

This task focuses on capturing and analyzing network traffic using
**Wireshark**.

Wireshark is a network protocol analyzer that allows us to capture,
filter, and inspect packets travelling through a network interface.

During this task, live network traffic was captured and different
protocols were identified using Wireshark display filters.

The main protocols identified were:

- 🌐 DNS
- 🔗 TCP
- 🔐 TLS

---

## 🎯 Objectives

The objectives of this task were:

- Install Wireshark.
- Capture live network traffic.
- Understand network packets.
- Apply Wireshark display filters.
- Identify at least three network protocols.
- Inspect individual packets.
- Save the network capture.
- Understand basic network-security concepts.

---

## 🖥️ Environment

| Item | Details |
|---|---|
| Operating System | Windows |
| System Type | 64-bit |
| Tool | Wireshark |
| Capture Type | Live Network Traffic |
| Protocols Identified | DNS, TCP, TLS |
| Capture File | `task5_network_capture.pcapng` |
| Status | ✅ Completed |

---

# 🔹 Step 1 — Install Wireshark

Wireshark was installed on the Windows computer.

During installation, the required packet-capture component was installed
so that Wireshark could access the network interface.

### 🧠 What is Wireshark?

**Wireshark** is a network protocol analyzer.

It allows security professionals and network administrators to:

- Capture packets
- Analyze network communication
- Troubleshoot network problems
- Identify protocols
- Investigate suspicious network activity

---

# 🔹 Step 2 — Select the Network Interface

After opening Wireshark, the available network interfaces were displayed.

The active interface showing network activity was selected.

For a laptop connected through Wi-Fi, this is normally the **Wi-Fi**
interface.

### 🧠 What is a Network Interface?

A network interface is the connection through which a computer
communicates with a network.

Examples:

- Wi-Fi
- Ethernet
- Bluetooth

---

# 🔹 Step 3 — Start Packet Capture

The active network interface was opened to start capturing packets.

While the capture was running, normal network activity generated
different packets.

### 🧠 What is a Packet?

A **packet** is a small unit of data transmitted through a network.

For example:

Your Laptop
     ↓
   Packet
     ↓
Network / Server
A packet contains information such as:

Source
Destination
Protocol
Ports
Packet data
🔹 Step 4 — Generate Network Traffic

Normal network activity was performed while Wireshark was capturing.

This generated different types of network packets.

The capture was then stopped after sufficient traffic had been collected.

🔹 Step 5 — Filter DNS Traffic

The following Wireshark display filter was used:

dns
🧠 What does dns mean?

dns tells Wireshark to display only packets identified as
DNS (Domain Name System) traffic.

DNS is responsible for translating domain names into IP addresses.

Example:

google.com
     ↓
DNS
     ↓
IP Address
Why did we use this filter?

It helps us isolate DNS traffic from thousands of other packets.

🔹 Step 6 — Filter TCP Traffic

The following display filter was used:

tcp
🧠 What does tcp mean?

tcp tells Wireshark to display packets using
Transmission Control Protocol.

TCP provides reliable, connection-oriented communication.

TCP packets can contain information such as:

Source Port
Destination Port
Sequence Number
Acknowledgment Number
TCP Flags
Why did we use this filter?

It allows us to focus specifically on TCP communication.

🔹 Step 7 — Filter TLS Traffic

The following display filter was used:

tls
🧠 What does tls mean?

tls filters packets associated with
Transport Layer Security.

TLS is used to protect network communication using encryption and
authentication.

Modern HTTPS websites commonly use TLS.

Why is TLS important?

Without encryption, sensitive information could potentially be exposed
during network communication.

TLS helps protect the contents of the communication.

🔹 Step 8 — Test HTTP Filter

The following filter was also tested:

http
🧠 What does http mean?

HTTP stands for Hypertext Transfer Protocol.

It is used for communication between web clients and web servers.

However, modern websites commonly use HTTPS, which is protected
using TLS.

Therefore, a capture may contain TLS traffic instead of visible
plain HTTP traffic.

📊 Protocols Identified
Protocol	Full Name	Purpose
DNS	Domain Name System	Resolves domain names
TCP	Transmission Control Protocol	Reliable network communication
TLS	Transport Layer Security	Protects network communication
HTTP	Hypertext Transfer Protocol	Web communication

The three main protocols identified for the task were:

DNS, TCP and TLS.

💾 Step 9 — Save the Packet Capture

The captured traffic was saved as:

task5_network_capture.pcapng
🧠 What is .pcapng?

.pcapng is a packet-capture file format.

It allows the captured network traffic to be saved and opened again
later in Wireshark.

This file is important evidence for the practical task.

📚 Important Technical Terms
1. Packet

A small unit of data transmitted over a network.

2. Protocol

A set of rules that computers use to communicate.

3. DNS

Domain Name System

Used to translate domain names into IP addresses.

4. TCP

Transmission Control Protocol

A connection-oriented protocol designed for reliable communication.

5. TLS

Transport Layer Security

A security protocol that helps encrypt and protect network communication.

6. HTTP

Hypertext Transfer Protocol

A protocol used for communication between web browsers and web servers.

7. HTTPS

HTTPS is HTTP protected using TLS.

It is commonly used by modern websites.

8. IP Address

A numerical address used to identify a device or network interface.

Example:

192.168.1.10
9. Port

A logical communication endpoint used by network applications.

Examples:

Port	Common Use
22	SSH
23	Telnet
53	DNS
80	HTTP
443	HTTPS
10. Display Filter

A Wireshark expression used to display only packets matching a
specific condition.

Examples:

dns
tcp
tls
http
🔍 Filter Summary
Filter	Shows	Why Used
dns	DNS packets	Analyze DNS traffic
tcp	TCP packets	Analyze TCP communication
tls	TLS packets	Analyze encrypted/protected traffic
http	HTTP packets	Check for plain HTTP traffic
🧠 What I Learned

Through this task, I learned:

How to use Wireshark.
How to capture live network traffic.
What a network packet is.
How to use Wireshark display filters.
How DNS works at a basic level.
How TCP is used for network communication.
Why TLS is important for secure communication.
How to inspect individual packets.
How to save a packet capture.
How packet analysis can be useful in cybersecurity.
🔐 Security Importance

Packet analysis is an important cybersecurity skill.

Security professionals can use tools such as Wireshark to:

Investigate network problems
Understand network communication
Identify unexpected protocols
Analyze suspicious traffic
Troubleshoot connectivity
Support security investigations

Network traffic analysis can help identify unusual communication
patterns and provide useful evidence during security investigations.

📸 Evidence

The practical included evidence of:

Screenshot 1 — Network Capture

Shows the Wireshark packet capture with live network traffic.

Screenshot 2 — DNS Analysis

Shows DNS packets after applying:

dns
Screenshot 3 — TCP Analysis

Shows TCP packets after applying:

tcp
Screenshot 4 — TLS Analysis

Shows TLS packets after applying:

tls

The original Wireshark capture file is also included:

task5_network_capture.pcapng
