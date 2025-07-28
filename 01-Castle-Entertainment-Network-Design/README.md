# Castle Entertainment Enterprise Network Evolution
*From Ground-Up IPv4 Design to Modern IPv6 Infrastructure*

## 🏢 Executive Summary
This project documents the complete network infrastructure evolution for Castle Entertainment, a rapidly growing TV/movie memorabilia company. As the lead network engineer, I was tasked with designing and implementing their entire network infrastructure from scratch, then modernizing it to meet changing business requirements.

**The Challenge:** Walk into an empty building and create a complete enterprise network infrastructure that would support 40+ users across multiple departments.

**The Evolution:** Successfully implement initial IPv4 multi-floor design, then adapt to business changes requiring IPv6 migration and facility consolidation.

### Project Phases Overview

| Phase | Challenge | Solution | Key Technologies |
|-------|-----------|----------|------------------|
|  1  | Design complete network infrastructure from scratch for 3-floor facility | IPv4 VLSM implementation with router-on-a-stick architecture | Cisco networking, VLAN segmentation, inter-VLAN routing |
|  2  | Modernize to IPv6 and consolidate to single floor while maintaining operations | IPv6 addressing with enhanced wireless and VLAN optimization | IPv6 protocols, wireless integration, network modernization |

## 📁 Project Documentation

### 🌐 Phase 1: IPv4 Multi-Floor Foundation

## Network Topology

phase1-logical-topology.png

## Configuration Files

### Router Configuration: 

Mian-Castle-Router_running-config.txt

### Switch Configurations:
Floor 1 Switch1: Sales-Switch1_running-config.txt

Floor 1 Switch1: Sales-Switch2_running-config.txt

Floor 2 Switch: Billing-Switch_running-config.txt

Floor 3 Switch: Executive-Switch_running-config.txt


## Network Validation and Testing

### Basic Ping Connectivity: 

basic-ping-test.png

### Inter-Subnet Ping Connectivity: 

inter-subnet-ping-test(01).png

inter-subnet-ping-test(02).png


## Packet Tracer Files

IPv4 Multi-Floor.pkt

### 🔄 Phase 2: IPv6 Single-Floor Modernization

## 🛠️ Technical Achievements

### Technologies Demonstrated
- **Networking Protocols:** IPv4, IPv6, TCP/IP, DHCP, DNS
- **Cisco Technologies:** IOS configuration, VLAN management, routing protocols
- **Network Security:** VLAN isolation, wireless security, access control
- **Design Tools:** Cisco Packet Tracer, network topology design
- **Documentation:** Technical documentation, configuration management

### Key Technical Skills Demonstrated
- **Network Design:** Physical and logical topology planning
- **Protocol Implementation:** IPv4 and IPv6 addressing and routing
- **VLAN Management:** Multi-VLAN segmentation and inter-VLAN routing
- **Wireless Integration:** Enterprise wireless deployment and security
- **Cost Optimization:** Single router solution with enterprise functionality

## 🎯 Key Engineering Decisions

### Phase 1 Critical Decisions
1. **Router-on-a-Stick Architecture**
   - *Why:* Single router budget constraint
   - *Impact:* Cost savings while maintaining enterprise functionality
   - *Trade-off:* Single point of failure accepted for cost optimization

2. **VLSM Addressing Strategy**
   - *Why:* Optimize limited 192.168.9.0/24 address space
   - *Impact:* Efficient IP allocation across varying department sizes
   - *Result:* 25% IP address space reserved for future growth

3. **Departmental VLAN Segmentation**
   - *Why:* Security isolation and executive oversight requirements
   - *Impact:* Enhanced security with controlled inter-departmental access
   - *Implementation:* 4 VLANs with selective routing policies

### Phase 2 Strategic Adaptations
1. **IPv6 Migration Strategy**
   - *Business Driver:* Future-proofing and ISP IPv6 allocation
   - *Approach:* Clean migration during facility consolidation
   - *Benefit:* Modern protocol stack with enhanced addressing

2. **Single-Floor Consolidation**
   - *Business Driver:* Operational efficiency and cost reduction
   - *Technical Challenge:* Maintain departmental isolation in open floor plan
   - *Solution:* Enhanced VLAN strategy with wireless integration

