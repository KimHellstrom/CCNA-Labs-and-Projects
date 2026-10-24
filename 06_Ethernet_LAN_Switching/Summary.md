# Lab 06: Ethernet LAN Switching

* **Source Material**: Jeremy's IT Lab (CCNA Day 6)
* **Objective**: Observe the MAC-Adress table of each switch during an ARP request.

## Topology Overview

Switching to simulation mode, it is an easier way to observe as the packet traverses through the L2 network system before being decapsulated by a switch.
The switch will store the source and destination MAC addresses inside its dynamic MAC address table.

### Packet information:
* **Source MAC**: Who is trying to establish the connection
* **Destination MAC**: The final destination of the packet, usually a server or another computer

## Verification Notes & Observations
* Verified packet sent and recieved:
  >ping ip-address: a quick way to confirm connection between devices

* Verified MAC-address table
  >show mac-address-table: shows currently stored mac addresses inside the table
  
  >clear mac-address-table: flushes the stored mac addresses inside the table


  ### extra:
  Inside the ARP table, we can also observe stored source and destination IP addresses belonging to L3
