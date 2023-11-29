# VirtualBox Networking Notes

## 1. Which network mode in VirtualBox can be used to emulate unplugging the Ethernet cable from the network?

### Disconnected Mode
- **Description:** Emulates unplugging the Ethernet cable.
- **Use Case:** Useful for testing scenarios where network connectivity needs to be simulated as offline.
- **Configuration in VirtualBox:** Set the network mode to "Disconnected."

*Reference:* [VirtualBox Network Setting Guide](https://www.nakivo.com/blog/virtualbox-network-setting-guide/)

## 2. Which network mode would be best if you wanted to run a server on a VM that could be fully accessible from your physical local area network?

### Bridged Adapter Mode
- **Description:** Enables a VM to be fully accessible from the physical local area network.
- **Use Case:** Running a server on a VM that requires external access.
- **Configuration in VirtualBox:** Set the network mode to "Bridged Adapter."

*Reference:* [VirtualBox Network Setting Guide](https://www.nakivo.com/blog/virtualbox-network-setting-guide/)

## 3. What are the three options of promiscuous mode and what does each do?

### Promiscuous Mode Options
- **Deny:**
  - *Description:* Prevents the VM from receiving traffic not explicitly addressed to it.
- **Allow VMs:**
  - *Description:* Permits the VM to receive traffic destined for other VMs on the same network.
- **Allow All:**
  - *Description:* Fully promiscuous mode, allowing the VM to receive all network traffic.
- **Use Case:** Configuring how the VM handles network traffic.
- **Configuration in VirtualBox:** Set the desired promiscuous mode in network settings.

*Reference:* [Professor Messer - Network Topologies](https://www.professormesser.com/network-plus/n10-008/n10-008-video/network-topologies-5/)

## 4. What is Port Forwarding?

### Port Forwarding
- **Description:** Technique for redirecting network traffic from one IP address and port to another.
- **Use Case:** Enabling external access to services running on a VM within a private network.
- **Configuration in VirtualBox:** Set up port forwarding rules for specific services.

*Reference:* [Professor Messer - Network Switching Overview](https://www.professormesser.com/network-plus/n10-008/n10-008-video/network-switching-overview-n10-008/)

## References:

- [VirtualBox Network Setting Guide](https://www.nakivo.com/blog/virtualbox-network-setting-guide/)
- [Professor Messer - Network Topologies](https://www.professormesser.com/network-plus/n10-008/n10-008-video/network-topologies-5/)
- [Professor Messer - Routing Technologies](https://www.professormesser.com/network-plus/n10-008/n10-008-video/routing-technologies-n10-008/)
- [Professor Messer - Dynamic Routing](https://www.professormesser.com/network-plus/n10-008/n10-008-video/n10-008-dynamic-routing/)
- [Professor Messer - Network Switching Overview](https://www.professormesser.com/network-plus/n10-008/n10-008-video/network-switching-overview-n10-008/)
