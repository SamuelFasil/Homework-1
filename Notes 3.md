# Notes 3
## 1, What is DHCP?
DHCP (Dynamic Host Configuration Protocol) is a network management protocol used to dynamically assign an Internet Protocol (IP) address to any device, or node, on a network so they can communicate using IP. DHCP automates and centrally manages these configurations rather than requiring network administrators to manually assign IP addresses to all network devices. DHCP can be implemented on small local networks, as well as large enterprise networks.

DHCP will assign new IP addresses in each location when devices are moved from place to place, which means network administrators do not have to manually configure each device with a valid IP address or reconfigure the device with a new IP address if it moves to a new location on the network. Versions of DHCP are available for use in IP version 4 (IPv4) and IP version 6 (IPv6). IPv6 became an industry standard in 2017 -- nearly 20 years after its specifications were first published. While the adoption rate of IPv6 was slow, by July 2019, more than 29% of Google users were making inquiries using IPv6.

### How DHCP works
DHCP runs at the application layer of the Transmission Control Protocol/IP (TCP/IP) stack to dynamically assign IP addresses to DHCP clients and to allocate TCP/IP configuration information to DHCP clients. This includes subnet mask information, default gateway IP addresses and domain name system (DNS) addresses.

DHCP is a client-server protocol in which servers manage a pool of unique IP addresses, as well as information about client configuration parameters, and assign addresses out of those address pools. DHCP-enabled clients send a request to the DHCP server whenever they connect to a network.

Clients configured with DHCP broadcast a request to the DHCP server and request network configuration information for the local network to which they're attached. A client typically broadcasts a query for this information immediately after booting up. The DHCP server responds to the client request by providing IP configuration information previously specified by a network administrator. This includes a specific IP address, as well as a time period -- also called a lease -- for which the allocation is valid. When refreshing an assignment, a DHCP client requests the same parameters, but the DHCP server may assign a new IP address based on policies set by administrators. DHCP clients can also be configured on an Ethernet interface.

A DHCP server manages a record of all the IP addresses it allocates to network nodes. If a node is relocated in the network, the server identifies it using its Media Access Control (MAC) address, which prevents the accidental configuration of multiple devices with the same IP address. Configuring a DHCP server also requires the creation of a configuration file, which stores network information for clients.

DHCP is not a routable protocol, nor is it a secure one. DHCP is limited to a specific local area network, which means a single DHCP server per LAN is adequate or two servers for use in case of a failover. Larger networks may have a wide area network (WAN) containing multiple individual locations. Depending on the connections between these points and the number of clients in each location, multiple DHCP servers can be set up to handle the distribution of addresses. If network administrators want a DHCP server to provide addressing to multiple subnets on a given network, they must configure DHCP relay services located on interconnecting routers that DHCP requests have to cross. These agents relay messages between DHCP clients and servers located on different subnets.

DHCP lacks any built-in mechanism that would enable clients and servers to authenticate each other. Both are vulnerable to deception -- one computer pretending to be another -- and to attack, where rogue clients can exhaust a DHCP server's IP address pool.

When managing many DHCP servers or DHCP servers in a WAN, users can make use of a command line. Users should also be aware that starting, stopping and restarting will affect the running of the daemon.

## 2, What is Firewall?
A firewall is a network security device that monitors incoming and outgoing network traffic and decides whether to allow or block specific traffic based on a defined set of security rules.

Firewalls have been a first line of defense in network security for over 25 years. They establish a barrier between secured and controlled internal networks that can be trusted and untrusted outside networks, such as the Internet. 

A firewall can be hardware, software, software-as-a service (SaaS), public cloud, or private cloud (virtual).

## Different types of firewalls
### Proxy firewall
An early type of firewall device, a proxy firewall serves as the gateway from one network to another for a specific application. Proxy servers can provide additional functionality such as content caching and security by preventing direct connections from outside the network. However, this also may impact throughput capabilities and the applications they can support.

### Stateful inspection firewall
Now thought of as a “traditional” firewall, a stateful inspection firewall allows or blocks traffic based on state, port, and protocol. It monitors all activity from the opening of a connection until it is closed. Filtering decisions are made based on both administrator-defined rules as well as context, which refers to using information from previous connections and packets belonging to the same connection.

### Unified threat management (UTM) firewall
A UTM device typically combines, in a loosely coupled way, the functions of a stateful inspection firewall with intrusion prevention and antivirus. It may also include additional services and often cloud management. UTMs focus on simplicity and ease of use.


### Next-generation firewall (NGFW)
Firewalls have evolved beyond simple packet filtering and stateful inspection. Most companies are deploying next-generation firewalls to block modern threats such as advanced malware and application-layer attacks.

According to Gartner, Inc.’s definition, a next-generation firewall must include:

Intelligence-based access control with stateful inspection
Integrated intrusion prevention system (IPS)
Application awareness and control to see and block risky apps
Upgrade paths to include future information feeds
Techniques to address evolving security threats
URL filtering based on geolocation and reputation
While these capabilities are increasingly becoming the standard for most companies, NGFWs can do more.

### Threat-focused NGFW
These firewalls include all the capabilities of a traditional NGFW and also provide advanced threat detection and remediation. With a threat-focused NGFW you can:

Know which assets are most at risk with complete context awareness
Quickly react to attacks with intelligent security automation that sets policies and hardens your defenses dynamically
Better detect evasive or suspicious activity with network and endpoint event correlation
Greatly decrease the time from detection to cleanup with retrospective security that continuously monitors for suspicious activity and behavior even after initial inspection
Ease administration and reduce complexity with unified policies that protect across the entire attack continuum


### Virtual firewall
A virtual firewall is typically deployed as a virtual appliance in a private cloud (VMware ESXi, Microsoft Hyper-V, KVM) or public cloud (Amazon Web Services or AWS, Microsoft Azure, Google Cloud Platform or GCP, Oracle Cloud Infrastructure or OCI) to monitor and secure traffic across physical and virtual networks. A virtual firewall is often a key component in software-defined networks (SDN).

Learn about Cisco virtual firewalls for public cloud and private cloud.

### Cloud Native Firewall
Cloud native firewalls are modernizing the way to secure applications and workload infrastructure at scale. With automated scaling features, cloud native firewalls enable networking operations and security operations teams to run at agile speeds.

### Advantages of Cloud Native Firewalls

Agile and elastic security
Multi-tenant capability
Smart load balancing
