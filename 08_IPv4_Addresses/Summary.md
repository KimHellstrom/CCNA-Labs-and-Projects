# Lab 08: IPv4 Addresses

* **Source Material**: Jeremy's IT Lab (CCNA Day 8)
* **Objective**: Observe initial router interfaces connectivity, and configure each interface to establish a connection between end devices across different networks.

## Topology Overview

A router is used to establish connection between 3 networks whom uses a PC end device.

### Interface information:
* **Adminstrative down, down**: The interface is currently shut down, unable to process information through the connected media.
* **Administrative up, down**: The interface is currently running, but there is a L1 issue, preventing the interface from sending and recieving data.
* **Administrative up, up**: The interface is currently running, and there is no issue with the media, the interface is able to send and recieve data. 

## Verification Notes & Observations
* Verified current state using the CLI:
>show interface: shows each interface status

>show running-config: shows currently running configured IPv4-address as well as status of the interface

* Verified saved configurations
>show startup-config: shows saved configurations of the interfaces


  ### extra:
  Configured IP addresses for each PC end-device, and tested their connectivity to eachothers network:
  >ping ip-address
