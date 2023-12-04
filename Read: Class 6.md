**1. What is the main purpose for implementing NAT on a network?**
   - NAT serves several purposes, including the conservation of IP addresses, enhanced security, simplification of network design, and facilitation of the IPv4 to IPv6 transition. ([GeeksforGeeks](https://www.geeksforgeeks.org/network-address-translation-nat/))

**2. At what layer of the OSI model does NAT happen?**
   - NAT typically operates at the Network Layer (Layer 3) of the OSI model. ([Professor Messer](https://www.professormesser.com/professor-messer-archives/n10-007/network-address-translation-3/))

**3. What happens to packets when NAT runs out of addresses in the pool of available IPs?**
   - When NAT runs out of addresses in the pool, it leads to "NAT exhaustion," and new devices attempting to establish connections may be unable to do so. Address pool expansion or other advanced NAT techniques may be required to address this issue. ([Professor Messer](https://www.professormesser.com/professor-messer-archives/n10-007/common-network-types/))

**4. What disadvantage does using NAT pose for routers?**
   - One disadvantage of using NAT for routers is that it can complicate certain network applications and protocols. This includes issues with peer-to-peer applications, some VPN configurations, and certain types of online gaming. Additionally, NAT can introduce latency and overhead in the routing process. ([Professor Messer](https://www.professormesser.com/professor-messer-archives/n10-007/ipv4-and-ipv6-addressing/))
xyc