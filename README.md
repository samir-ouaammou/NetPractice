## 🧠 What will you gain from NetPractice?
NetPractice will help you build a strong foundation in networking by giving you practical, hands-on experience. You will:
- Understand how networks work at a deep level, not just theory.
- Learn essential concepts like IP addressing, subnetting, routing, NAT, DNS, DHCP, and more.
- Practice building, configuring, and troubleshooting real network topologies.
- Develop logical thinking and problem-solving skills that are crucial for IT and cybersecurity careers.

---

![image](https://github.com/user-attachments/assets/373af781-f439-46c0-a8da-a8193edebb58)

---
![Screenshot from 2025-05-28 13-37-47](https://github.com/user-attachments/assets/47db444a-cd95-4b46-8456-87ac6c45a57e)


## 🌐 What is a Network?
A network is a group of devices (computers, phones, printers, etc.) connected together to share information and resources. Networks can be wired (using cables) or wireless (using Wi-Fi). The main goal is to allow devices to communicate, share files, printers, and access the internet.

---

## 🎯 Why Do We Use Networks?
- **Resource sharing:** Share files, printers, and internet connections between devices.
- **Communication:** Enable email, messaging, video calls, and collaboration.
- **Centralized management:** Manage devices and data from a central location.
- **Scalability:** Easily add new devices and users.

---

## 📌 Types of Networks:
- **LAN (Local Area Network):** Small area, like a home, office, or school. Fast and secure.
- **MAN (Metropolitan Area Network):** Connects multiple LANs in a city or campus.
- **WAN (Wide Area Network):** Covers large areas, like countries or continents. The internet is the largest WAN.

---

## 🌐 What is LAN?
A Local Area Network (LAN) connects devices in a small area, such as a home, office, or school. LANs are fast, secure, and allow easy sharing of resources like files and printers.

---

## 🏙️ What is MAN?
A Metropolitan Area Network (MAN) connects multiple LANs within a city or large campus. It is larger than a LAN but smaller than a WAN, and is used by organizations with buildings spread across a city.

---

## 🌍 What is WAN?
A Wide Area Network (WAN) covers a large area, such as a country or the whole world. The internet is the biggest WAN, connecting millions of networks globally.

---

## ⚙️ Basic Network Components:
- **Router:** Connects your local network to the internet and routes data between networks.
- **Switch:** Connects multiple devices within the same LAN and forwards data to the correct device.
- **Gateway:** Entry/exit point between different networks, often between a LAN and the internet.
- **IP Address:** Unique number assigned to each device for identification and communication.

---

## 🔌 What is Ethernet?
Ethernet is a technology for connecting devices in a wired local network (LAN). It uses cables (like RJ45) to provide fast and stable connections between computers, printers, and other devices.

---

## 🌐 What is an IP Address?
An IP Address (Internet Protocol Address) is a unique number assigned to each device on a network. It acts like a postal address, allowing data to be sent to the right device.

---

## Types of IP Addresses:
- **Private IP:** Used inside your local network (e.g., 192.168.1.10). Not accessible from the internet.
- **Public IP:** Used on the internet, assigned by your ISP. Identifies your network globally.
- **Static IP:** Manually set and does not change. Used for servers or devices that need a permanent address.
- **Dynamic IP:** Automatically assigned and can change over time. Used for most home devices.

---

## 🌐 What is a Public IP?
A Public IP is assigned by your Internet Service Provider (ISP) and is used to identify your network on the internet. It allows your devices to communicate with servers and other devices worldwide.

---

## 🌐 What is a Private IP?
A Private IP is used only within your local network (home, office). Devices with private IPs cannot be accessed directly from the internet, which adds a layer of security.

---

## 🌐 What is a Static IP?
A Static IP is a fixed address manually assigned to a device. It never changes, making it ideal for servers, printers, or devices that need a permanent address.

---

## 🌐 What is a Dynamic IP?
A Dynamic IP is automatically assigned by a DHCP server and can change each time a device connects to the network. It’s useful for devices that don’t need a permanent address.

---

## 🌐 What is a MAC Address?
A MAC (Media Access Control) address is a unique identifier assigned to a network interface card (NIC) by the manufacturer. It is used for communication within the local network and is written in hexadecimal (e.g., 00:1A:2B:3C:4D:5E).

---

## 🌐 What is a Subnet?
A Subnet divides a large network into smaller, more manageable sections (subnetworks). This helps organize devices, improve performance, and enhance security. Subnetting uses a subnet mask to define which part of an IP address refers to the network and which part to the device.

![Screenshot from 2025-05-28 13-20-36](https://github.com/user-attachments/assets/11da51ae-d829-42a8-b00f-d1ecf17e5a90)



---

## 🌐 What is a Network Address?
The Network Address identifies the entire network or subnet. Routers use it to send data to the correct network.

---

## 🌐 What is a Host Address?
The Host Address identifies a specific device within a network or subnet. Each device must have a unique host address in its subnet.

---

## 🌐 What is a Broadcast Address?
A Broadcast Address is used to send data to all devices on a network at once. For example, 192.168.1.255 in a typical home network.

---

## 🌐 What is a Loopback Address?
127.0.0.1 is the loopback address. It lets a device send data to itself, useful for testing network software or configurations.

---

## 🌐 What is the OSI Model?
The OSI Model (Open Systems Interconnection) is a conceptual framework that describes how data moves through a network in 7 layers:
1. **Physical:** Transmits raw bits over cables or wireless.
2. **Data Link:** Ensures reliable connection between two devices (uses MAC addresses).
3. **Network:** Routes data between networks (uses IP addresses).
4. **Transport:** Ensures data is delivered reliably (TCP/UDP).
5. **Session:** Manages sessions (connections) between applications.
6. **Presentation:** Translates, encrypts, or compresses data.
7. **Application:** Where user applications access network services (web, email, etc.).

![Screenshot from 2025-05-28 12-59-06](https://github.com/user-attachments/assets/f15d2d05-7407-45ae-930b-d129851fe5e4)

---

## 🌐 What is the TCP/IP Model?
The TCP/IP Model is the foundation of the internet. It has 4 layers:
1. **Network Access / Link:** Handles physical transmission on the local network (Ethernet, Wi-Fi).
2. **Internet:** Routes packets between networks (IP).
3. **Transport:** Provides reliable (TCP) or fast (UDP) data transfer.
4. **Application:** Provides services for user applications (HTTP, FTP, DNS, etc.).

![Screenshot from 2025-05-28 13-09-29](https://github.com/user-attachments/assets/00f88653-e942-4ed9-be29-c07d1e247c78)

---

![Screenshot from 2025-05-28 13-13-41](https://github.com/user-attachments/assets/5e14c76f-4847-4aad-8df8-40b850f12b16)

---

## 🌐 What is TCP?
TCP (Transmission Control Protocol) is a reliable, connection-oriented protocol. It ensures all data arrives in order and without errors. Used for web browsing, email, file transfers.

---

## 🌐 What is UDP?
UDP (User Datagram Protocol) is a fast, connectionless protocol. It doesn’t guarantee delivery or order, but is great for streaming, gaming, and voice calls.

---

## 🌐 What is a Protocol?
A protocol is a set of rules that define how data is transmitted and received over a network. Examples include TCP, UDP, HTTP, and FTP.

---

## 🌐 What is a Packet?
A packet is a small chunk of data sent over a network. Large messages are broken into packets, which are sent separately and reassembled at the destination.

---

## 🌐 What is a Switch?
A switch is a device that connects multiple devices in a LAN and forwards data only to the intended device using MAC addresses. This reduces unnecessary traffic and improves network efficiency.

---

## 🌐 What is a Router?
A router is a device that forwards data between different networks (like your home network and the internet). It decides the best path for data to travel using routing tables and algorithms.

---

## 🌐 What is a Gateway?
A gateway connects two different networks and translates data between them. It’s often used to connect a local network to the internet, and can also provide firewall, NAT, or proxy services.

---

## 🌐 What is DHCP?
DHCP (Dynamic Host Configuration Protocol) automatically assigns IP addresses and network settings to devices when they join a network. This makes network management easier and reduces errors.

---

## 🌐 What is NAT?
NAT (Network Address Translation) allows multiple devices on a local network to share a single public IP address. It helps conserve public IP addresses and adds security by hiding internal devices.

---

## 🌐 What is DNS?
DNS (Domain Name System) translates human-friendly domain names (like google.com) into IP addresses that computers use to communicate. This makes it easier for users to access websites without remembering numeric IPs.

---

## 📖 Recommended Resources

- [YouTube: Network Direction - Networking Basics](https://www.youtube.com/@NetworkChuck/playlists) — Video playlist for visual learners.
- [YouTube: Network Direction - Networking Basics](https://www.youtube.com/@ITDose22/playlists) — Video playlist for visual learners.

---

## ✨ Summary        
NetPractice is not just a theoretical project, but an interactive experience that teaches you to think like a network engineer. You'll leave with a solid understanding of how devices communicate, the steps to set up a network properly, and the ability to solve network issues on your own.


Thank you for checking out my NetPractice project! Stay tuned for more exciting challenges. 🔥
