# Lab 11: Troubleshooting static routes

* **Source Material**: Jeremy's IT Lab (CCNA Day11)
* **Objective**: Troubleshooting and troublesolving connectivity issues with a WAN.

## Topology Overview

A fully functioning WAN consisting of 2 PCs, 2 Switches and 3 Routers.

### Troubleshooting findings:
* **Request timed out**: TTL have exceeded the count, packet either couldn't reach the destination or was lost during transmission.
* **Reply from IP-address: Destination host unreachable**: Routing malconfigurations

## Verification Notes & Observations
* Verified errors:
  - Found IP-address malconfiguration
  - Found routing malconfigurations
  - Found Network media malconfigurations

* Verified solution:
  >ping IP-address: Confirming if there is a properly configured network connection between two devices



  ### extra:
  It is crucial that all devices has a properly installed cabling/wireless if possible to operate.
  
  Router -> Router requires cross-over cabling in this instance.
