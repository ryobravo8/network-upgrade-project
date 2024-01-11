#New Network Design Overview:
**•	Building Structure:** Contemporary three-level office structure, encompassing a total area of 45,000 square feet.
**•	 Floor Allocation:**
	o	First Floor: Houses Sales, Marketing, HR, and Logistics departments, covering 15,000 square feet.
	o	Second Floor: Dedicated to Finance, Accounts, Administration, and PR, also spanning 15,000 square f	eet.
	o	Third Floor: Hosts ICT and the Server Room, occupying 15,000 square feet.	
**•	Offices and Connectivity:** Around 60 individual offices amid open-plan spaces. Newly designed independent network with potential for integration with the existing network.
**•	Client Categories:**
	o	Each department: Supports 120 users with various devices.
	o	Server Room: Manages 12 devices.
**•	Wireless Clients:** Maximum capacity of 1,320 clients (accounting for 600 employees with 2 devices each and an additional 10% for guests/extra devices).
**•	Public Client Support:** Dedicated guest network for internet access, segregated from the main internal network.
**•	Server Needs:**
	o	Required services include File, Domain, DNS, Web, Email, Database, Application, DHCP, Backup and Recovery, Network Management and Monitoring, VPN, and Print Servers.
	o	Generally 1-2 units per service for redundancy and load management.
**•	Internet and Domain Hosting:** Internet connectivity via various ISPs, domain likely maintained by an external provider, with the mail server being either in-house or hosted.

**•	Network Overview:**
	o	Current: Basic configuration with constrained capacity and old hardware.
	o	Desired: Enhanced capacity, improved redundancy, advanced security, efficient network partitioning, modernized wireless access, and sophisticated network management.

**•	High-Level Solutions:**
	o	Strategies include augmenting capacity, bolstering redundancy, fortifying security, redesigning the network, upgrading wireless capabilities, and enhancing monitoring and management.

**•	Network Design Outline:**
	o	7 separate networks/subnets for 6 departments plus a guest network.
	o	VLAN implementation for each department.
	o	Utilization of Cisco routers and switches, with a variety of cable types.

**•	Future Upgrade Plan:**
	o	Workstation growth: Anticipating a modest yearly growth rate of 10%, the network could be expected to support an extra 60 workstations in one year, summing up to approximately 660 workstations.
	o	Connection speed upgrades: Annual reassessment of bandwidth needs, with potential upgrades to 10-gigabit Ethernet for central switches and more robust routers if necessary.
	o	Wireless access point enhancements: 
			Capacity: Considering the growth in wireless device usage (BYOD culture and IoT devices), more access points might be needed for optimal performance.
			Technology: Staying updated with wireless technology advancements, such as Wi-Fi 6E or newer standards, for improved speed, capacity, and reduced latency.
