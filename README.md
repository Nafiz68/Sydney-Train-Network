# CSE421 Project - Sydney Train Network Simulation

## Overview
This project is a comprehensive network design and simulation for the Sydney Train Network, created as part of the CSE421 Computer Networks course. The project demonstrates the implementation of a large-scale network infrastructure using Cisco Packet Tracer, modeling the communication and data transmission requirements of a metropolitan train network system.

## Project Description
The Sydney Train Network simulation implements a real-world network scenario that encompasses multiple train stations, control centers, and communication systems across the Sydney metropolitan area. This project demonstrates practical applications of networking concepts including:

- **Network Topology Design**: Multi-site network architecture connecting various train stations and control centers
- **Routing Protocols**: Implementation of dynamic routing protocols for efficient data transmission
- **VLANs and Subnetting**: Logical network segmentation for different departments and functions
- **Network Security**: Implementation of access control lists (ACLs) and security policies
- **Quality of Service (QoS)**: Priority-based traffic management for critical train operations
- **Redundancy and Fault Tolerance**: Backup paths and failover mechanisms for network reliability

## Project Files
- **Group201_421_project.pkt**: Main Cisco Packet Tracer project file containing the complete network topology, device configurations, and simulation scenarios
- **Project Details.pdf**: Comprehensive documentation of project requirements, specifications, and implementation details
- **2. Sydney Train Network.pdf**: Additional documentation with network diagrams, addressing schemes, and technical specifications

## Network Architecture
The network design includes:

### Core Components
- **Central Control Center**: Main hub for network management and train operations control
- **Station Networks**: Individual network segments for each train station
- **Communication Links**: Inter-station connectivity and backbone infrastructure
- **Backup Systems**: Redundant paths and failover configurations

### Device Types
- Routers for inter-network communication
- Switches for local area network connectivity
- Servers for centralized services (DNS, DHCP, Web, etc.)
- End devices simulating station computers, ticketing systems, and monitoring equipment

### Network Services
- Dynamic Host Configuration Protocol (DHCP) for automatic IP assignment
- Domain Name System (DNS) for name resolution
- Web services for information dissemination
- File Transfer Protocol (FTP) for data exchange
- Monitoring and management systems

## Technical Specifications

### Addressing Scheme
The network utilizes a hierarchical IP addressing structure with proper subnetting to accommodate:
- Multiple station locations
- Different departments and functions
- Scalability for future expansion
- Efficient address utilization

### Routing Configuration
- Implementation of dynamic routing protocols (RIP, EIGRP, or OSPF)
- Static routes for specific network segments
- Default routes for internet connectivity
- Route summarization for optimal routing tables

### VLAN Implementation
- Administrative VLAN for management traffic
- Operations VLAN for train control systems
- Public VLAN for passenger information systems
- Security VLAN for surveillance and monitoring
- Voice VLAN for communication systems

### Security Measures
- Access Control Lists (ACLs) to restrict unauthorized access
- Port security on switches
- Password protection on network devices
- Encrypted communications for sensitive data
- Network segmentation for isolation

## Requirements

### Software
- **Cisco Packet Tracer** (Version 7.3 or higher recommended)
  - Download from the [Cisco Networking Academy website](https://www.netacad.com/courses/packet-tracer)
  - Requires free Cisco NetAcad account registration

### System Requirements
- Operating System: Windows 7/8/10/11, macOS, or Linux
- RAM: Minimum 4GB (8GB recommended for large simulations)
- Processor: Dual-core processor (Quad-core recommended)
- Disk Space: 500MB free space
- Display: 1024x768 resolution minimum

## How to Use

### Opening the Project
1. Install Cisco Packet Tracer on your computer
2. Launch the application
3. Navigate to File → Open
4. Browse to the project directory and select `Group201_421_project.pkt`
5. Wait for the project to load completely

### Exploring the Network
1. **Logical View**: Examine the overall network topology and device interconnections
2. **Physical View**: Explore the physical layout and device placement
3. **Device Configuration**: Click on individual devices to view their configurations
4. **Simulation Mode**: Use the simulation feature to observe packet flow and network behavior

### Testing the Network
1. **Connectivity Tests**: Use ping commands to test end-to-end connectivity
2. **Protocol Analysis**: Examine routing tables and protocol operations
3. **Traffic Simulation**: Generate network traffic to test performance
4. **Failure Scenarios**: Simulate link failures to test redundancy mechanisms

### Running Simulations
1. Switch to **Simulation Mode** using the bottom-right panel
2. Add filters for specific protocols (ICMP, HTTP, DNS, etc.)
3. Click on **Auto Capture/Play** to observe packet transmission
4. Use **Edit Filters** to focus on specific types of traffic
5. Analyze the **Event List** to understand packet-level details

## Learning Objectives
This project demonstrates understanding of:
- Network topology design principles
- IP addressing and subnetting
- Routing protocol configuration and operation
- VLAN configuration and inter-VLAN routing
- Network security implementation
- Quality of Service (QoS) configuration
- Network troubleshooting methodologies
- Documentation and project presentation skills

## Key Features Implemented
- ✅ Hierarchical network design with core, distribution, and access layers
- ✅ Multiple interconnected sites representing different stations
- ✅ Dynamic routing protocol implementation
- ✅ VLAN segmentation for different services
- ✅ DHCP for dynamic IP address assignment
- ✅ DNS for name resolution services
- ✅ ACLs for security policy enforcement
- ✅ Redundant paths for fault tolerance
- ✅ QoS for prioritizing critical traffic
- ✅ Comprehensive device labeling and documentation

## Testing and Validation
The network has been tested for:
- **Connectivity**: All devices can communicate within their authorized scope
- **Routing**: Proper route propagation and convergence
- **Security**: ACLs effectively restrict unauthorized access
- **Redundancy**: Network maintains functionality during link failures
- **Performance**: Adequate bandwidth and low latency for critical services
- **Scalability**: Design supports addition of new stations and services

## Project Team
- **Group 201**
- **Course**: CSE421 - Computer Networks
- **Institution**: [Your University Name]
- **Semester**: [Semester/Year]

## Deliverables
1. Cisco Packet Tracer file with complete network implementation
2. Project documentation (Project Details.pdf)
3. Network diagrams and specifications (Sydney Train Network.pdf)
4. Configuration files for all network devices
5. Testing results and validation reports
6. Project presentation materials

## Troubleshooting

### Common Issues
1. **Devices not communicating**:
   - Check IP addressing and subnet masks
   - Verify routing table entries
   - Confirm VLAN assignments
   - Test physical connectivity

2. **Routing protocol not working**:
   - Verify protocol is enabled on all interfaces
   - Check network statements in routing configuration
   - Ensure no passive interfaces block updates
   - Verify authentication settings if configured

3. **DHCP not assigning addresses**:
   - Confirm DHCP server configuration
   - Check DHCP pool settings
   - Verify helper-address on router interfaces
   - Ensure no IP conflicts exist

4. **Access denied errors**:
   - Review ACL configurations
   - Check ACL placement (interface and direction)
   - Verify permit/deny statements
   - Ensure ACL is applied to correct interface

## Future Enhancements
Potential improvements and extensions to this project:
- Implementation of IPv6 addressing
- Integration of wireless networks for mobile devices
- Advanced QoS policies for video surveillance
- VPN connectivity for remote management
- Network automation using Python scripts
- Integration with real-time monitoring tools
- Implementation of Software-Defined Networking (SDN) concepts

## References and Resources
- Cisco Packet Tracer Documentation
- Cisco IOS Command Reference
- Computer Networks Textbook (Tanenbaum or Kurose & Ross)
- RFC documents for protocol specifications
- Cisco Networking Academy course materials
- Online networking communities and forums

## License and Usage
This project is created for educational purposes as part of the CSE421 course. 
- **Academic Use**: Freely available for learning and reference
- **Commercial Use**: Not permitted without authorization
- **Modification**: Encouraged for learning purposes with proper attribution

## Notes
- **Backup**: Always save your work with incremental filenames (e.g., project_v1, project_v2) to preserve different versions
- **Performance**: Large simulations may require significant system resources; close unnecessary applications
- **Compatibility**: Ensure you're using a compatible version of Packet Tracer to avoid issues
- **Documentation**: Refer to the included PDF files for detailed specifications and requirements
- **Support**: Contact your course instructor or teaching assistants for project-specific questions

## Acknowledgments
We would like to thank:
- Our course instructor for guidance and support
- Teaching assistants for technical assistance
- Cisco Networking Academy for providing Packet Tracer
- Sydney Trains for inspiration and reference materials
- Fellow students for collaboration and feedback

---

**Last Updated**: January 2026  
**Version**: 1.0  
**Status**: Completed
