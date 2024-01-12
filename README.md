# Network Upgrade Project

## Overview
This project involves a comprehensive plan for upgrading an existing network infrastructure to enhance performance and security. The design and implementation are based on the assignment from McGill University's cybersecurity course.

## Objectives
- Upgrade the network infrastructure.
- Enhance performance and security.
- Implement advanced networking features.

## Existing Network Overview

- **Capacity:** Initially intended for a smaller user base, currently experiencing bottlenecks and decreased efficiency.
- **Hardware:** Obsolete networking devices, such as routers and switches, unable to cope with present data flow and security requirements.
- **Redundancy:** Absence of multiple Internet service providers and backup systems, leading to critical vulnerabilities.
- **Security:** Primitive security setup, inadequate for protection against contemporary cyber threats.
- **Design:** Suboptimal layout with ineffective VLAN distribution, compromising both network performance and safety.
- **Wireless Access:** Restricted range and archaic Wi-Fi standards, falling short of present-day usage expectations.

## Network Design

This section outlines our New Network Design for a modern three-story, 45,000 sq ft office building. It features a meticulously planned network to support various departments with distinct needs, ensuring robust infrastructure and advanced connectivity. Key highlights include optimized floor allocation, enhanced office connectivity, comprehensive client support, and future-proof server solutions. Detailed technical specifications, hardware lists, and floor plans are available in the [Network_Design](https://github.com/ryobravo8/network-upgrade-project/tree/main/Network_Design) folder.

## Implementation Details
The network was implemented using Cisco IOS commands, as documented in the 'Code' folder. A Packet Tracer simulation was used for demonstration, available in the [Packet_Tracer_File](https://github.com/ryobravo8/network-upgrade-project/tree/main/Pacekt_Tracer_file) folder.

## Challenges and Solutions
### Challenge: RIP Configuration

One of the key challenges faced during the implementation of our network upgrade project was configuring the Routing Information Protocol (RIP). RIP is a dynamic routing protocol used in local and wide area networks. As a distance-vector routing protocol, it employs the hop count as a routing metric and uses the Bellman-Ford algorithm to determine the best path to each destination network. The challenge lay in correctly configuring RIP to ensure efficient and accurate routing within our upgraded network.

### Solution: Implementing Cisco IOS Commands for RIP

To address this challenge, we employed a series of Cisco IOS commands specifically designed for RIP configuration. Here's a step-by-step breakdown of the commands used:
1. Enable RIP Routing Process
  - `router rip`: This command initiates the RIP routing process
2. Specify the RIP Version
  - `version 2`: We chose RIP version 2 for its support of subnetting and CIDR.
3. Define the Networks
  - `network [network-address]`: This command is repeated for each network connected to the router. The network address should be the network number, not the IP address of the router's interface.
4. Optional Commands
  - `no auto-summary`: Disables automatic summarization of subnet routes into network-level routes.
  - `passive-interface [interface-name]`: Prevents RIP updates from being sent through a specified interface, useful for security and traffic optimization.
5. Save Configuration
  - `write memory`: This command saves the configuration to prevent loss after a reboot.

By implementing these steps, we successfully configured RIP for our network, ensuring effective routing and addressing the challenge efficiently.

## Future Improvements
(Outline potential future enhancements to the network.)

## Screenshots
(Include screenshots from the Packet Tracer simulation here.)

## References
- YouTube Video: Gurutech Networking Training (2022, July 14). Company Network Design & Implementation Using Cisco Packet Tracer | Enterprise Network Project #6. YouTube. https://youtu.be/eqEd84yeRxg?si=fa2i9BFFPmilTcdO

## Acknowledgements
Special thanks to Gurutech Networking Training for the insightful video titled "Company Network Design & Implementation Using Cisco Packet Tracer | Enterprise Network Project #6", which provided valuable guidance and inspiration for this project. Their work on Enterprise Network Desigining was particularly helpig in completing this project


---

This project was developed as part of the coursework for the cybersecurity program at McGill University. All network designs and implementations are based on the requirements of the course assignment.

Please feel free to contribute or suggest improvements through Issues or Pull Requests.
