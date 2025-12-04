Computer Networks Lab Tasks
Overview

This repository contains a series of lab tasks that demonstrate various aspects of computer networking. Each task involves configuring different network components using Cisco Packet Tracer, including PC-to-PC connections, switch-router setups, DHCP configurations, wireless network configurations, and more.

Labs Overview

Lab 1: PC to PC Connection

Objective: Set up a direct PC-to-PC connection using Cisco Packet Tracer.

Components:

2 PCs

1 Copper Cross-Over Cable

Steps:

Add two PCs to the workspace.

Use a Copper Cross-Over Cable to connect them.

Assign static IP addresses.

Test the connection using a ping command.

Lab 1.1: Multiple PCs Connected through One Hub

Objective: Connect multiple PCs using a hub.

Components:

1 Hub

4 PCs

Straight-Through Cables

Steps:

Add devices and connect them to the hub.

Assign static IP addresses to all PCs.

Test connectivity with simple PDU.

Lab 1.2: Multiple PCs Connected through Two Hubs

Objective: Extend the previous lab by adding another hub and multiple PCs.

Components:

2 Hubs

5 PCs

1 Laptop

Steps:

Connect PCs and laptops to hubs.

Assign IP addresses to all devices.

Test connectivity.

Lab 2: Switch-to-Switch Connection via Bridge

Objective: Configure switches and bridge to connect multiple devices across two subnets.

Components:

2 Switches

1 Bridge

3 PCs

1 Laptop

Steps:

Set up devices and connect them.

Configure IP addresses for all devices.

Test connectivity between subnets using a bridge.

Lab 3: Multiple Devices Across Two Subnets Using Router

Objective: Set up multiple devices across two subnets with a router.

Components:

1 Router

2 Switches

4 PCs

1 Laptop

Steps:

Connect devices and configure IP addresses.

Set up routing between two subnets.

Test communication between devices in different subnets.

Lab 4: DHCP Configuration

Objective: Set up a DHCP server to dynamically assign IP addresses to devices.

Components:

Server configured with DHCP

Router and Switch

Various PCs

Steps:

Enable DHCP on the server.

Configure devices to use DHCP.

Test DHCP functionality.

Lab 4.1: Wireless Router Configuration

Objective: Set up a wireless router to allow wireless devices to communicate with wired devices.

Components:

Wireless Router

Router

3 Laptops/PCs

Steps:

Configure router and wireless router settings.

Set up wireless security (WEP).

Connect wireless devices and test connectivity.

Lab 5: Router-to-Router Connection

Objective: Configure a router-to-router connection to route traffic between two networks.

Components:

2 Routers

1 Switch

Laptops/PCs

Steps:

Set up router interfaces.

Configure static routing between networks.

Test the connection.

Requirements

To run these labs, you will need:

Cisco Packet Tracer (latest version)

Basic knowledge of networking concepts (IP addresses, subnetting, routing)

How to Use

Clone this repository:

git clone https://github.com/yourusername/network-labs.git


Open the .pkt files in Cisco Packet Tracer.

Follow the lab steps to configure each network.

Verify connectivity by sending packets or pinging devices.

Contributing

Feel free to fork this repository, make your changes, and submit a pull request.

License

This project is licensed under the MIT License.
