# Week 05 Tutorial — View-Routes-12327823

## 1. Project Overview
Created the **View-Routes-12327823** project.

![Project introduction](images/week5-intro.png)

## 2. Topology
Topology consists of 2 Linux Hosts connected via a Linux Router and a switch: **Host — Router — Switch — Host**.

![Topology diagram](images/week5-menu.png)

## 3. Starting the Nodes
Started all nodes in the topology.

![All nodes started](images/week5-1.png)

## 4. Routing Configuration
Reviewed the routing table on each device.

![Routing table 1](images/week5-2.png)
![Routing table 2](images/week5-3.png)

## 5. Network Connectivity Test (Ping)
Verified end-to-end connectivity using ping.

![Ping test result 1](images/View-Routes-12327823.png)
![Ping test result 2](images/View-Routes-12327823-2.png)

## 6. Dynamic Routing with OSPF

Imported the OSPF project and started all nodes.

![OSPF project imported and started](images/OPSF.png)

Used the three FRR `show ip` commands to inspect routing information.

![FRR show ip command 1](images/week5-FSSR-1.png)
![FRR show ip command 2](images/week5-FRR-2.png)

### Traceroute
Ran a traceroute to confirm the path taken across the OSPF-routed network.

![Traceroute result](images/traceroute.png)
