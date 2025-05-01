## 🌐 NetPractice — An Engaging and Practical Introduction to the World of Networking        
NetPractice is one of the networking projects at 1337/42 School, designed to help you understand how networks operate in practice, not just theoretically. You work with a network simulator, where you can build networks, configure addresses, and learn how communication happens between devices step by step.        


## 🧠 What will you gain from NetPractice?             
🔹 A deep understanding of how networks work "under the hood."        
🔹 Key concepts like: IP Address, Subnet Mask, Gateway, Routing, NAT, DNS, DHCP...        
🔹 Hands-on experience: Build networks yourself, discover errors, and troubleshoot.        
🔹 Strong logical and organizational skills in solving networking problems.        
🔹 Excellent preparation for fields like Cybersecurity, System Administration, DevOps, or Network Engineering.        


## 🌐 Quick Introduction to the World of Networking        
What is a network?        
A network is a collection of devices connected to each other (via cables or Wi-Fi) for the purpose of exchanging data.        


## 🎯 Why do networks exist?        

File and printer sharing        
Internet access for multiple devices        
Facilitating communication within organizations        


## 📌 Types of Networks:        
LAN (Local Area Network): Inside a home or office        
MAN (Metropolitan Area Network): Covers a city        
WAN (Wide Area Network): Like the internet        


## ⚙️ Network Components:        
Router: Connects the network to the outside world        
Switch: Connects devices internally                
Gateway: Where data exits the network        
IP Address: The unique identifier for each device        


## 🧩 NetPractice is divided into 10 levels:        
### 📍 Level 0 — IP Basics        
✅ The difference between IP and MAC        
✅ Why does each device need a unique IP?        
✅ What happens if we give an incorrect IP?        


### 📍 Level 1 — Basic Communication        
✅ How do two devices in the same network communicate?        
✅ What is Ping? And how do we know the connection is successful?        


### 📍 Level 2 — Same Network        
✅ The role of the Subnet Mask in distinguishing devices within the same network        
✅ Understanding the Network ID and the importance of configuring the Mask        


### 📍 Level 3 — Gateways        
✅ What is the Default Gateway?        
✅ Why do we need a Gateway to leave the local network?        


### 📍 Level 4 — Routing Basics        
✅ The difference between a Router and a Gateway        
✅ How does a device determine the path to an external network?        


### 📍 Level 5 — Routing Setup        
✅ Setting up a Router for the first time        
✅ Each Interface needs an IP        


### 📍 Level 6 — Multi-routing        
✅ How devices communicate with multiple networks        
✅ The role of the Routing Table in directing data        


### 📍 Level 7 — Subnetting        
✅ How to split a large network into smaller subnets        
✅ Calculating the Network Address and Broadcast Address        


### 📍 Level 8 — Advanced Routing        
✅ The difference between Static Routing and Dynamic Routing        
✅ When do we need to manually configure routes?        


### 📍 Level 9 — Complex Networks        
✅ Challenges in large networks        
✅ Issues like Routing Loops and how to choose the best solution        


## 📚 Complementary Concepts Essential for NetPractice:        
#### 🔌 Ethernet:        
A wired connection technology between devices in a local network, known for speed and stable connectivity.        

#### 🌐 IP Address:        
A unique numeric address for each device.        
🔸 Private IP: Used within the local network        
🔸 Public IP: Used on the internet        
🔸 Static IP: Does not change        
🔸 Dynamic IP: Changes automatically through DHCP        

#### 🧩 Subnet:        
Dividing a network into smaller subnets for improved performance and security.        
🔹 Network Address: Identifies the network        
🔹 Host Address: Identifies the device within the network        
🔹 Broadcast Address: Sends data to all devices        

#### 🌀 Loopback Address:        
A special address (127.0.0.1) used to test communication within the device itself (localhost).        

# ---Let’s take a quick look at some basic networking ideas.---


## 🌐 What is a Network?   
A network is a group of devices connected together to exchange data and information, using methods like cables or Wi-Fi.   


## 🎯 Why Do We Use Networks?   
🔹 To share files and printers.   
🔹 To access the internet from multiple devices.   
🔹 To make communication between users easier.   


## 📌 Types of Networks:   
🔹 LAN (Local Area Network): Covers a small area like a home or office.   
🔹 WAN (Wide Area Network): Covers a large area, like the internet.   
🔹 MAN (Metropolitan Area Network): Covers an entire city.   


## ⚙️ Basic Network Components:   
🔹 Router: Connects the network to the internet.   
🔹 Switch: Connects multiple devices within the local network.   
🔹 IP Address: Uniquely identifies each device on the network.   
🔹 Gateway: The access point for data to exit the local network.   


## 🌐 What is LAN?   
LAN stands for Local Area Network.   
🔹 It means: "Local Network"   
🔹 It connects a group of devices within a limited and small geographic area such as a: 🏠 Home, 🏢 Office, or 🏫 School.   
🔹 These networks are used to share data and resources like printers and files among connected devices.   


## 🏙️ What is MAN?   
MAN stands for Metropolitan Area Network.   
🔹 It means: "Urban Network" or "City-Level Network"   
🔹 It connects a group of Local Area Networks (LANs) within the same city or metropolitan area.   
#### A MAN is larger than a LAN but smaller than a WAN, and it's used to provide connectivity between organizations or facilities within the city.   


## 🌍 What is WAN?   
WAN stands for Wide Area Network.   
🔹 It means: "Wide Coverage Network"   
🔹 It connects devices over very large distances, such as across cities, countries, or even the entire world.   
#### The internet is the largest example of a WAN, as it links millions of networks and devices worldwide.   


## 🔌 What is Ethernet?   
Ethernet is a technology used to connect electronic devices within a wired network.   
🔹 It is one of the most common technologies in Local Area Networks (LAN) for enabling communication between devices via network cables.   
🔹 It provides high and stable connection speeds.   


## 🌐 What is an IP Address?   
An IP Address (Internet Protocol Address) is a unique numerical label assigned to each device connected to a network, allowing it to identify itself and communicate with other devices.   
It is like a home address, used to pinpoint the location of a device within the network.   
#### Types of IP Addresses:   
🔹 Private IP: Used within a local network.   
🔹 Public IP: Used on the internet.   
🔹 Static IP: Does not change.   
🔹 Dynamic IP: Changes automatically.   
#### Summary:   
An IP Address is the device's identification card on the network. Without it, data exchange or communication with other devices is not possible.   


## 🌐 What is a Public IP?   
A Public IP is an address assigned to your device or router by your Internet Service Provider (ISP), used to connect to the external world via the internet.   
🔹 Features of Public IP:   
🔹 Used to communicate with devices and servers on the internet.   
🔹 Identifies your network or device on the global network.   
🔹 Exposed to direct access from the internet, so it requires strong protection.   
🔹 Essential for tasks like website hosting or remote access.   
#### Summary:     
A Public IP is your "global address" on the internet, enabling you to send and receive data from anywhere, but it requires proper security measures.   


## 🌐 What is a Private IP?   
A Private IP is an IP address used within private networks (LANs) like homes or businesses.   
🔹 It cannot be accessed directly from the internet.   
🔹 The Private IP is used within local networks (LAN) (like homes or businesses) and cannot be accessed directly from the internet.      
#### Features of Private IP:   
🔹 Cannot be accessed directly from the internet.   
🔹 Used for communication between devices within the same network only.   
🔹 Contributes to security, as it is not directly exposed to internet attacks.   
🔹 Automatically assigned by a device like a router using DHCP.   


## 🌐 What is a Static IP?   
A Static IP (Static Internet Protocol Address) is an address that is manually assigned to a specific device within the network and remains constant over time, even after the device is rebooted.   
#### Features of Static IP:   
🔹 Fixed: The address stays the same permanently.   
🔹  Manually Assigned: Set by the network administrator or through the device settings.   
#### Useful for devices that require a stable connection, such as:   
🔹 Servers   
🔹 Network printers   
🔹 Surveillance cameras   
🔹 Network-attached storage (NAS)   
#### In summary:   
A Static IP is an address that doesn't change and is used for devices that need a permanent and stable address within the network, ensuring continuous connection and service.      


## 🌐 What is a Dynamic IP?   
A Dynamic IP is an IP address that is automatically assigned to devices by a DHCP server. It is temporary and may change each time the device reconnects to the network.   
#### Features of Dynamic IP:   
🔹 Automatically Assigned: Given when the device connects to the network.   
🔹 Variable: It may change after each restart or after a certain period.   
🔹 Used to conserve addresses in networks with many devices.   
🔹 Ideal for regular devices (such as smartphones, computers, and home appliances) that don't require a permanent address.   
##### In summary:   
A Dynamic IP is a variable address automatically assigned to your device when connecting, making it easier to manage addresses in large networks.   


## 🌐 What is a MAC Address?   
MAC Address stands for Media Access Control Address. It is a unique identifier assigned to a network interface card (NIC) for communication on the physical network.   
#### Key Facts about MAC Address:   
🔹 It is hardcoded into the device's network hardware by the manufacturer.   
🔹 It looks like this: 00:1A:2B:3C:4D:5E (6 pairs of hexadecimal numbers).   
🔹 Used in local network communication (like in a LAN), not across the internet.   
#### How is it used?   
🔹 Switches and routers use MAC addresses to forward data to the correct device in a local network.   
🔹 Can be used to control network access (MAC filtering).   
#### Summary:   
A MAC address is a permanent, unique hardware address assigned to each network device. It helps identify devices on the local network and plays a critical role in data delivery within a LAN.   


## 🌐 What is a Subnet?   
A Subnet (or Subnetwork) is the division of a larger network into smaller networks to improve network management and efficiency. Subnets are used to break down a large network into smaller sub-networks, helping to organize data traffic, reduce congestion, and enhance security.   
#### How does a Subnet work?   
A Subnet works by splitting an IP address into two parts:   
1. Network Address: Used to identify the subnetwork.   
2. Host Address: Used to identify a device within the subnetwork.   
This process is used primarily in IPv4 and IPv6, and subnets are determined using a Subnet Mask, which is a series of numbers that specify which part of the IP address belongs to the network and which part belongs to the device.   
##### Advantages of Subnetting:   
🔹 Improved Performance: Dividing the network reduces data congestion and increases network speed.   
🔹 Security: Controls data traffic between subnets, reducing security threats.   
🔹 Easier Management: Dividing the network into smaller subnets makes management easier, especially in large networks.   
##### In summary:   
A Subnet is the division of a large network into smaller networks, helping to improve network performance, provide security, and simplify management.   


## 🌐 What is a Network Address?   
A Network Address identifies the entire network and is used to route data to the specific subnet. It is the part of the IP address that refers to the network itself.   


## 🌐 What is a Host Address?   
A Host Address identifies a specific device within the network and distinguishes each device from others within the same network. It is the part of the IP address used for addressing individual devices.   


## 🌐 What is a Broadcast Address?   
A Broadcast Address is used to send data to all devices in the network simultaneously. It allows communication with every device on the network at once.   


## 🌐 What is a Loopback Address?   
127.0.0.1 (Loopback Address) is used to test the connection to the same device. Data sent to this address is routed back to the device itself, allowing it to communicate with itself for testing purposes.   


## 🌐 What is the OSI Model?   
The OSI (Open Systems Interconnection) Model is a conceptual framework used to understand how systems interact in a network. It consists of seven layers:   
#### 1. Physical Layer   
Definition: Responsible for transmitting raw data over physical mediums (wires, fiber optics, wireless signals).   
Responsibilities: Converts data into signals that can be transmitted through physical media.   
#### 2. Data Link Layer   
Definition: Responsible for establishing a reliable connection between two devices on the network.   
Responsibilities: Ensures data is delivered correctly, handles errors, and manages access to the medium.   
#### 3. Network Layer   
Definition: Responsible for routing data across the network.   
Responsibilities: Determines the best path for data using protocols like IP.   
#### 4. Transport Layer   
Definition: Ensures reliable data transfer between devices.   
Responsibilities: Divides data into smaller packets, ensures correct delivery using protocols like TCP and UDP.   
#### 5. Session Layer   
Definition: Manages sessions between applications.   
Responsibilities: Controls and terminates sessions between devices and ensures the continuity of the connection.   
#### 6. Presentation Layer   
Definition: Responsible for translating data so that it can be understood by the applications.   
Responsibilities: Data formatting, encryption, compression, and transformation.   
#### 7. Application Layer   
Definition: The closest layer to the user, where applications interact with the network.   
Responsibilities: Provides services like HTTP for web browsing, FTP for file transfer, etc.   
#### Summary:   
The OSI Model helps in understanding how data is transmitted across networks by breaking the process into seven layers, each responsible for a specific part of data transfer, from the physical medium to the final application.   


## 🌐 What is TCP?   
TCP stands for Transmission Control Protocol.   
It is a protocol responsible for transferring data between devices in a reliable and orderly manner, ensuring that all data arrives intact and error-free.   
#### How does TCP work?   
🔹 First, a connection is established between the two devices (Client ↔️ Server) before data is transmitted (called a 3-way handshake).   
🔹 The data is divided into small chunks (Packets).   
🔹 Each packet is tracked and confirmed as received.   
🔹 If any packet is lost, TCP will retransmit it.   
🔹 Once all the data is received, the connection is closed.   
#### Features of TCP:   
🔹 Reliable: Ensures all data is delivered without errors.   
🔹 Ordered: Assembles the data in the correct sequence.   
🔹 Retransmits missing data automatically.   
🔹 Slower than other protocols (like UDP) due to safety and error-checking steps.   
#### Summary:   
TCP is the protocol responsible for sending data securely and in an organized manner between devices, making sure it is reliable and error-free.   


🌐 What is UDP?   
UDP (User Datagram Protocol) is a protocol used for transmitting data between devices. It is characterized by sending data quickly, but without ensuring its arrival or proper order.   
#### How does it work?   
🔹 Direct: Sends data directly without prior connection (no 3-way handshake).   
🔹 No Guarantees: Does not confirm whether data arrives or in what order.   
🔹 Fast: Known for fast data transmission in scenarios that require quick information delivery.   
#### Features of UDP:   
🔹 Fast: No time spent retransmitting or verifying data.   
🔹 Unreliable: Data may be lost or arrive out of order.   
🔹 Low resource usage: Consumes minimal memory and processing power.   
#### When do we use it?   
🔹 Internet voice calls (VoIP).   
🔹 Online gaming.   
🔹 Live video streaming.   
#### Summary:   
UDP is a fast but unreliable protocol, used in applications where speed of data transfer is more important than the accuracy of data delivery.   


## 🌐 What is a Protocol?   
A protocol is a set of rules and guidelines that define how devices or systems communicate with each other over a network. It is the agreed-upon method for exchanging data between devices in a specific way.   


## 🌐 What is a Packet?   
A packet is a small unit of data that is sent over a network. When the data is large, it is broken into several small packets that are sent independently across the network, and then reassembled at the receiving end to form the original data.   
#### In Summary:
A packet is a small unit of data transmitted over a network. Large data is divided into smaller packets for efficient transmission, and they are reassembled at the receiving end to recover the original data   


## 🌐 What is a Switch?   
A switch is a network device used to connect multiple devices (like computers, printers, or servers) within the same local area network (LAN). It uses MAC addresses to forward data only to the specific device it’s intended for, rather than broadcasting it to all devices on the network.   
#### How it works:   
🔹 When a device sends data, the switch receives it.   
🔹 The switch checks the destination MAC address.   
🔹 It then forwards the data only to the port connected to the destination device.   
#### Key Features of a Switch:    
🔹 Improves network efficiency by reducing unnecessary traffic.   
🔹 Operates at Layer 2 (Data Link Layer) of the OSI model.   
🔹 Can be managed (managed switch) or unmanaged (plug-and-play).   
🔹 Supports full-duplex communication (devices can send and receive at the same time).   
#### In Summary:   
A switch is a smart network device that connects devices in a LAN and forwards data intelligently based on MAC addresses, making the network faster and more efficient.   


## 🌐 What is a Gateway?   
A gateway is a network device that acts as a bridge between two different networks, often connecting a local network (LAN) to the internet. It translates data between different network protocols, allowing communication between systems that wouldn’t otherwise understand each other.   
#### Key Role:    
A gateway is commonly used to connect internal networks (like your home or office network) to external networks (like the internet).   
#### How It Works:   
🔹 Devices on your local network send data to the gateway when trying to reach an external address.   
🔹 The gateway routes this data to the appropriate external network (like the internet).   
🔹 It also handles incoming data from the internet and forwards it to the correct device in your local network.   
#### Key Features:   
🔹 Works at Layer 3 (Network Layer) and above in the OSI model.   
🔹 Can be a dedicated device (like a router with gateway functionality) or a software-based system.   
🔹 Often combines other functions like firewall, NAT, or proxy services.   
#### In Summary:   
A gateway connects your local network to the outside world (usually the internet), translating and routing data between different networks and protocols.   


## 🌐 What is a Router?   
A router is a networking device that forwards data packets between different networks, typically between your local network (LAN) and the internet (WAN). It decides the best path for data to travel to its destination.   
#### Main Function:    
Routers direct traffic—they determine where to send data based on IP addresses.   
#### How It Works:   
🔹 When a device (like your phone or PC) sends a request to access a website, the router:   
1. Receives the packet from your device.   
2. Checks the destination IP address.   
3. Forwards it to the correct next stop (often your ISP or the internet).   
4. Handles incoming data and delivers it to the right device on your network.   
#### Key Features:   
🔹 Works at Layer 3 (Network Layer) of the OSI model.   
🔹 Uses routing tables and algorithms to decide the best route.   
🔹 Can connect multiple devices to the internet using one public IP (via NAT).   
🔹 Often includes features like firewall, DHCP, and Wi-Fi in home routers.   
#### In Summary:    
A router connects your local devices to other networks (like the internet) and manages the traffic flow, ensuring data goes where it needs to.   


## 🌐 What is DHCP?   
DHCP (Dynamic Host Configuration Protocol) is a network protocol used to automatically assign IP addresses and other network configuration settings (like gateway and DNS) to devices on a network—without manual setup.   
#### How it works:   
1. A device connects to the network and sends a DHCP Discover request.   
2. The DHCP server responds with an available IP address and settings.   
3. The device receives and uses the configuration for a limited time (lease time).   
#### Benefits of DHCP:   
🔹 Simplifies network management.   
🔹 Saves time and reduces human errors.   
🔹 Efficiently reuses IP addresses when devices disconnect.   
🔹 Automatically configures devices with the correct network settings.   
#### In Summary:    
DHCP automates the assignment of IP addresses and configuration, making networks easy to manage, especially when many devices are connected.   


## 🌐 What is NAT?   
NAT (Network Address Translation) is a technique used to translate IP addresses between a private internal network (like your home Wi-Fi) and the public network (like the Internet).   
#### How it works:   
🔹 Devices in a local network use private IP addresses.   
🔹 When one of these devices wants to access the Internet, NAT converts its private IP to a public IP.   
🔹 The router keeps track of this translation so that when a response comes back, it knows which internal device to forward it to.   
#### Why NAT is useful:   
🔹 Conserves public IP addresses: Many devices can share one public IP.   
🔹 Adds security: External devices can't directly access private IPs.   
🔹 Simplifies internal networking: Devices communicate freely inside the LAN.   
#### In Summary:    
NAT is a method that allows many internal devices to share a single public IP address, improving IP address efficiency, adding a layer of security, and making network management easier.   


## 🌐 What is DNS?   
DNS stands for Domain Name System. It is like the phonebook of the internet, translating human-friendly domain names (like google.com) into IP addresses (like 142.250.190.14) that computers use to identify each other.   
#### How does DNS work?   
🔹 You type a domain name in your browser (e.g., www.example.com).   
🔹 Your device asks a DNS server to find the IP address for that domain.   
🔹 The DNS server searches (or asks other DNS servers) for the correct IP.   
🔹 Once found, the IP address is returned, and your browser connects to that server.   
#### Why DNS is important:   
🔹 User-friendly: You don’t need to remember IP numbers.   
🔹 Scalable: Supports the massive number of websites and services on the internet.   
🔹 Supports security features like DNSSEC to prevent spoofing.   
#### Summary:   
DNS is a crucial system that converts domain names into IP addresses, allowing users to browse the web easily without needing to memorize numbers.   



## ✨ Summary:        
NetPractice is not just a theoretical project, but an interactive experience that teaches you to think like a network engineer. You'll leave with a solid understanding of how devices communicate, the steps to set up a network properly, and the ability to solve network issues on your own.        


