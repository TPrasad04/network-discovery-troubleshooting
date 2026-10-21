Network Discovery and Connectivity Troubleshooting

Project Overview

A beginner cybersecurity networking project performed on Windows 11 to understand IP addressing, DNS, DHCP, routing, and connectivity troubleshooting.

Objectives

- Identify IPv4 addressing and subnet configuration.
- Understand DHCP and DNS.
- Test local and gateway connectivity.
- Inspect routing tables and ARP cache entries.
- Examine network paths using traceroute.

Environment and Tools

- Windows 11
- Command Prompt
- "ipconfig"
- "ping"
- "nslookup"
- "route print"
- "arp"
- "tracert"

Network Configuration

Parameter| Value
IPv4 Address| 192.168.1.12
Subnet Mask| 255.255.255.0
CIDR Prefix| /24
Network ID| 192.168.1.0
Broadcast Address| 192.168.1.255
Default Gateway| 192.168.1.1
DHCP Server| 192.168.1.1
DNS Server| 192.168.1.1

Practical Results

Test| Result
Local loopback ping| Replies received
Gateway ping| Replies received
DNS lookup for example.com| Successful
Ping to 1.1.1.1| Replies received
Ping to example.com| Replies received
Default route| Found via 192.168.1.1
ARP gateway entry| Found
Traceroute| Some intermediate hops timed out; later hops responded

Key Learnings

- IPv4 addressing and CIDR notation
- Subnet masks and network IDs
- DHCP and DNS fundamentals
- Default gateways and routing tables
- ARP and local network communication
- Basic connectivity troubleshooting

Conclusion

This project provided practical experience with Windows networking commands and basic network troubleshooting. It establishes a foundation for future work in packet analysis, network security monitoring, and SOC operations.

Evidence

Screenshots of the practical commands and their results are included in this repository.

Disclaimer

This project was conducted on my own Windows computer and network. Results describe the tests performed during the lab and do not constitute a full security assessment.
