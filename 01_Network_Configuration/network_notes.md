# Network Configuration Notes

## Lab Network

The Wazuh SOC lab consisted of three main systems:

| System | Role | IP Address |
|---|---|---|
| Wazuh VM | Wazuh Manager and Dashboard | 192.168.1.164 |
| Kali Linux | Security Workstation | 192.168.1.142 |
| Windows 11 Host | Monitored Endpoint | 192.168.1.143 |

All systems were configured to communicate on the same network.

---

## Initial Kali Linux Network Issue

When I initially configured Kali Linux to use a Bridged Adapter in VirtualBox, the network interface did not receive a proper IP address.

The output showed an address beginning with:

```text
169.254.x.x