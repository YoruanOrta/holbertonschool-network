# Network - Holberton School

This repository contains comprehensive networking projects and exercises covering fundamental network concepts, protocols, and practical applications. The projects explore networking from theoretical foundations to hands-on implementation, demonstrating mastery of network administration, protocol analysis, and system connectivity.

## 📋 Description

**Comprehensive Networking Curriculum** covering essential networking concepts including:
- **OSI Model** - Understanding the seven-layer network architecture
- **Network Types** - LAN, WAN, and network topology concepts
- **Addressing Systems** - MAC addresses, IP addressing, and subnetting
- **Transport Protocols** - UDP and TCP protocol analysis
- **Port Management** - Network port configuration and monitoring
- **Network Diagnostics** - Tools and techniques for network troubleshooting
- **Practical Applications** - Real-world networking scenarios and solutions

## 👨‍💻 Author

**Yoruan Orta**
- GitHub: [@YoruanOrta](https://github.com/YoruanOrta)
- Project: Network Fundamentals and Administration

## 🗂️ Project Structure

```
holbertonschool-network/
├── basics_0/                   # Networking Fundamentals - Part 1
│   ├── 0-OSI_model             # OSI Model concepts and layers
│   ├── 1-types_of_network      # Network types and classifications
│   ├── 2-MAC_and_IP_address    # Addressing systems comparison
│   ├── 3-UDP_and_TCP           # Transport protocol analysis
│   ├── 4-TCP_and_UDP_ports     # Port numbers and applications
│   ├── 5-is_the_host_on_the_network # Network connectivity testing
│   └── README.md               # Basics 0 documentation
├── basics_1/                   # Networking Fundamentals - Part 2
│   ├── 0-change_your_home_IP   # IP address configuration
│   ├── 1-show_attached_IPs     # Network interface analysis
│   ├── 2-port_listening_on_localhost # Local port monitoring
│   └── README.md               # Basics 1 documentation
├── what_happens_when_your_type_google_com/ # Deep Dive Analysis
│   ├── 0-blog_post.md          # Technical blog post
│   ├── 1-what_happen_when_diagram # Network flow diagram
│   └── README.md               # Process analysis documentation
└── README.md                   # Main project documentation
```

## 🚀 Technology Stack

- **Shell (100%)** - Network administration and scripting
- **Bash Scripting** - Automation and system configuration
- **Network Tools** - ping, netstat, ss, ifconfig, ip
- **System Administration** - Linux networking configuration
- **Documentation** - Technical writing and diagramming

## 📚 Learning Modules

### **🌐 Networking Basics #0** (`basics_0/`)

#### **OSI Model** (`0-OSI_model`)
- **Seven-layer architecture** understanding
- **Layer responsibilities** and data encapsulation
- **Protocol mapping** to OSI layers
- **Communication flow** between layers

#### **Types of Network** (`1-types_of_network`)
- **LAN (Local Area Network)** characteristics and use cases
- **WAN (Wide Area Network)** infrastructure and connectivity
- **Internet** as a global network of networks
- **Network topology** concepts and implementations

#### **MAC and IP Address** (`2-MAC_and_IP_address`)
- **MAC Address** - Hardware-level addressing
- **IP Address** - Network-level addressing
- **Address Resolution Protocol (ARP)** functionality
- **Addressing hierarchy** and packet routing

#### **UDP and TCP** (`3-UDP_and_TCP`)
- **UDP (User Datagram Protocol)** - Connectionless communication
- **TCP (Transmission Control Protocol)** - Reliable connection-oriented protocol
- **Protocol comparison** - Speed vs reliability trade-offs
- **Use case scenarios** for each protocol

#### **TCP and UDP Ports** (`4-TCP_and_UDP_ports`)
- **Well-known ports** (0-1023) and their applications
- **Registered ports** (1024-49151) assignment
- **Dynamic/Private ports** (49152-65535) usage
- **Port scanning** and security implications

#### **Network Connectivity Testing** (`5-is_the_host_on_the_network`)
- **ICMP ping** protocol implementation
- **Network reachability** testing methods
- **Packet loss analysis** and interpretation
- **Troubleshooting connectivity** issues

### **🔧 Networking Basics #1** (`basics_1/`)

#### **IP Configuration** (`0-change_your_home_IP`)
- **Static IP assignment** vs DHCP
- **Network interface configuration**
- **Localhost and loopback** interface management
- **IP address conflict resolution**

#### **Network Interface Analysis** (`1-show_attached_IPs`)
- **Active network connections** monitoring
- **Interface status** and configuration display
- **IP address enumeration** techniques
- **Network adapter management**

#### **Port Monitoring** (`2-port_listening_on_localhost`)
- **Local service discovery** on localhost
- **Port binding** and service identification
- **Network service management**
- **Security auditing** of open ports

### **🔍 Deep Dive Analysis** (`what_happens_when_your_type_google_com/`)

#### **Technical Blog Post** (`0-blog_post.md`)
- **Complete network flow** from browser to server
- **DNS resolution** process and hierarchy
- **HTTP/HTTPS** request lifecycle
- **Load balancing** and content delivery

#### **Network Flow Diagram** (`1-what_happen_when_diagram`)
- **Visual representation** of network processes
- **Component interaction** mapping
- **Protocol stack** visualization
- **Infrastructure overview** diagrams

## ⚙️ Setup and Usage

### Prerequisites
```bash
# Linux/Unix environment
uname -a

# Network utilities (usually pre-installed)
which ping
which netstat
which ss
which ifconfig
which ip
```

### Running Network Commands

#### **Basic Network Information**
```bash
# View network interfaces
ifconfig -a
# or modern alternative
ip addr show

# Display routing table
route -n
# or modern alternative
ip route show

# Show network statistics
netstat -tuln
# or modern alternative
ss -tuln
```

#### **Connectivity Testing**
```bash
# Test network connectivity
ping -c 4 google.com

# Test specific port connectivity
telnet google.com 80

# Trace network route
traceroute google.com
```

#### **Port and Service Analysis**
```bash
# Show listening ports
netstat -tuln | grep LISTEN

# Show processes using network
lsof -i

# Monitor network traffic
tcpdump -i eth0
```

### Project-Specific Commands

#### **Basics 0 Examples**
```bash
cd basics_0/

# OSI Model demonstration
cat 0-OSI_model

# Network type classification
cat 1-types_of_network

# Address comparison
cat 2-MAC_and_IP_address

# Protocol analysis
cat 3-UDP_and_TCP

# Port identification
cat 4-TCP_and_UDP_ports

# Connectivity test
bash 5-is_the_host_on_the_network
```

#### **Basics 1 Examples**
```bash
cd basics_1/

# IP configuration
sudo bash 0-change_your_home_IP

# Show active IPs
bash 1-show_attached_IPs

# Monitor localhost ports
bash 2-port_listening_on_localhost
```

## 🎯 Learning Objectives

By completing this project, I have mastered:

### **Network Fundamentals:**
- ✅ OSI Model layers and their functions
- ✅ Network types and topology understanding
- ✅ Addressing systems (MAC vs IP) comprehension
- ✅ Transport protocol differences and applications

### **Protocol Knowledge:**
- ✅ TCP reliable connection-oriented communication
- ✅ UDP connectionless fast communication
- ✅ Port numbering and service identification
- ✅ ICMP for network diagnostics and testing

### **Network Administration:**
- ✅ IP address configuration and management
- ✅ Network interface monitoring and control
- ✅ Port scanning and service discovery
- ✅ Network troubleshooting methodologies

### **Practical Skills:**
- ✅ Command-line network utilities usage
- ✅ Network connectivity testing and validation
- ✅ System administration for networking
- ✅ Security assessment of network services

## 🔧 Network Tools Mastered

### **Connectivity Tools**
- **ping** - Network reachability testing
- **traceroute** - Path discovery and latency analysis
- **telnet** - Port connectivity testing
- **curl/wget** - HTTP/HTTPS testing and data retrieval

### **Information Gathering**
- **ifconfig/ip** - Network interface configuration
- **netstat/ss** - Network connection and port monitoring
- **lsof** - Process and file descriptor analysis
- **arp** - ARP table management and analysis

### **Monitoring and Analysis**
- **tcpdump** - Packet capture and analysis
- **wireshark** - GUI-based network protocol analyzer
- **nmap** - Network discovery and security auditing
- **iftop** - Real-time network bandwidth monitoring

## 💡 Key Networking Concepts

### **OSI Model Layers**
1. **Physical** - Hardware transmission medium
2. **Data Link** - Frame formatting and error detection
3. **Network** - Routing and logical addressing (IP)
4. **Transport** - End-to-end communication (TCP/UDP)
5. **Session** - Connection establishment and management
6. **Presentation** - Data encryption and compression
7. **Application** - User interface and network services

### **Network Addressing**
- **MAC Address**: Hardware-based, 48-bit identifier
- **IP Address**: Network-based, 32-bit (IPv4) or 128-bit (IPv6)
- **Subnet Mask**: Network and host portion definition
- **Default Gateway**: Router for inter-network communication

### **Transport Protocols**
- **TCP Features**: Connection-oriented, reliable, ordered delivery
- **UDP Features**: Connectionless, fast, minimal overhead
- **Port Numbers**: Application identification and multiplexing
- **Well-known Services**: HTTP(80), HTTPS(443), SSH(22), DNS(53)

## 🔍 Network Analysis Process

### **"What Happens When You Type google.com"**

1. **DNS Resolution**
   - Browser cache check
   - Operating system DNS cache
   - Recursive DNS server query
   - Root nameserver → TLD → Authoritative nameserver

2. **Connection Establishment**
   - TCP three-way handshake
   - TLS/SSL handshake for HTTPS
   - Certificate validation

3. **HTTP Request/Response**
   - HTTP request formatting and transmission
   - Load balancer routing
   - Web server processing
   - Response generation and delivery

4. **Content Rendering**
   - HTML parsing and DOM construction
   - CSS and JavaScript loading
   - Resource optimization and caching

## 🏆 Project Highlights

- **Comprehensive Coverage**: Complete networking fundamentals curriculum
- **Practical Application**: Real-world network administration tasks
- **Tool Proficiency**: Mastery of essential networking utilities
- **Security Awareness**: Understanding of network security principles
- **Documentation**: Technical writing and diagram creation skills
- **Problem Solving**: Network troubleshooting methodologies

## 📊 Skills Assessment

### **Technical Proficiency**
- Network protocol analysis and implementation
- System administration and configuration
- Command-line tool mastery
- Security assessment and monitoring

### **Analytical Skills**
- Network flow analysis and optimization
- Problem diagnosis and resolution
- Performance monitoring and tuning
- Documentation and communication

### **Professional Skills**
- Technical writing and documentation
- Diagram creation and visualization
- Systematic troubleshooting approach
- Security-conscious network management

## 👨‍💻 Author

**Yoruan Orta**
- GitHub: [@YoruanOrta](https://github.com/YoruanOrta)
- Repository: [holbertonschool-network](https://github.com/YoruanOrta/holbertonschool-network)
- Project: Holberton School Network

## 📄 License

This project is part of the Holberton School curriculum and is intended for educational purposes only.

---

⭐ **Holberton School** - Network Fundamentals | 2025

> *"The network is the computer." - John Gage, Sun Microsystems*