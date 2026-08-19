# Week 02 Tutorial

## 1. Project Setup
Created a new project named **Setting-IP-12327823**.

![New project created](images/week2-1.png)

## 2. Network Topology
Added four Linux Host nodes and one Ethernet switch, then connected them together to form a LAN.

![LAN topology with 4 hosts and a switch](images/Week2-Allss.png)

## 3. IP Address Configuration

### Host 1 & Host 2
Configured IPv4 addresses starting at `10.10.1.11` for Host 1 and Host 2.

![Host 1 & 2 IP configuration](images/week2-2.png)
![Host 1 & 2 IP configuration confirmation](images/week2-22.png)

Host 3 and Host 4 were left without the configure option applied at this stage. All nodes were then started.

### Host 3 — Static IP via Config File
Used `nano /etc/network/interfaces` on Host 3 to manually configure a static IP address of `10.10.1.13`.

![Static IP configuration on Host 3](images/week2-3.png)

### Host 4 — Static IP via Command
Used the `ip address add` command on Host 4 to assign an IP address to the host.

![IP address added on Host 4](images/week2-4.png)

## 4. Verifying IP Addresses
Confirmed that all IP addresses were correctly assigned across the four hosts.

![IP verification 1](images/week2-5.png)
![IP verification 2](images/week2-6.png)
![IP verification 3](images/week2-7.png)
![IP verification 4](images/week2-8.png)

## 5. Ping Tests

**Pinging Host 2** — successful reply confirming connectivity:

![Ping to Host 2 successful](images/Ping-Basics-12327823-simple.png)

**Pinging a random IP not included in the host configuration** — expected failure:

![Ping to unconfigured IP fails](images/Ping-Basics-12327823-Error.png)
