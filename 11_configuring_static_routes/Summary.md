# Lab 11: Configuring static routes

* **Source Material**: Jeremy's IT Lab (CCNA Day 11)
* **Objective**: Configuring routers and PC end-devices to establish a connection.

## Topology Overview

3 networks forming a WAN, consisting of 3 routers and 2 PCs and 2 Switches.

### Routing information:
* **Static Routing**: a manual L3 configuration allowing hop-to-hop between routers when destination IP-address lies beyond the LAN.
* **Static Routes**:
  -  Network - destination network IP-address.
  -  Mask - subnetmask of the destination network.
  -  Next Hop - Interface IP-address of closest next Router.

## Verification Notes & Observations
* verified the WAN connection:
  >ping IP-address: Confirms that there is an established connection between the PC end-devices.

* verified the saved routing configuration:
  >show startup-configure: Confirming interface configuration and descriptions, including routing details (inside Router CLI).

  ### extra:
  If there is a routing malconfiguration, a way to spot it is to use the **ping**-command, on a Windows computer,
  it'll say: "Request timed out" with the help of to TTL,
  reffering to the packet unable to reach its destination in time or was lost in the process.
