# Lab 02: Connecting Devices (+ configuration)

* **Source Material**: Jeremy's IT Lab (CCNA Day 2)
* **Objective**: Identify and connect interfaces with the correct media. Plus trying to set up the network to ping two end devices from seperate networks.

## Topology Overview

The network simulates established connected devices between several networks and a static configuration of L2 and L3. 

### Cables Used:
* **Copper straightthrough**: between switches and end devices/routers 
* **Cross-over**: between switches and between routers
* **Multi mode fiber**: between routers of 350m apart
* **"Single mode fiber"**: between routers of 3km apart.
  Unfortunately due to the limitation of prechosen routers and a lack of SFP module of these routers,
  i had to suffice with connecting a Multi mode fiber to a NM-1FGE module instead to get the network going, although i recognize that it wouldn't suffice in a wider
  area than 500m due to the type of cable.

## Verification Notes & Observations
* Verified chosen media for each interface and configuration of each static ip address, default gateway, subnetmask and network hop with CLI
* Used commands: 
  - >ipconfig to confirm configured ip addresses
  - >ping "ip-address" to verify local and internet connection
