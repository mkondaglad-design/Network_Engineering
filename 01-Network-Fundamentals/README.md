# Basic LAN Configuration & Connectivity

## Objective

Build and configure a basic Local Area Network (LAN) using two PCs and a Cisco switch.

## Topology

PC1 --------\
             \
              SW1
             /
PC2 --------/

## IP Addressing

| Device | Interface | IP Address | Subnet Mask |
|---|---|---|---|
| PC1 | NIC | 192.168.1.10 | 255.255.255.0 |
| PC2 | NIC | 192.168.1.20 | 255.255.255.0 |
| SW1 | VLAN 1 | 192.168.1.2 | 255.255.255.0 |

## Tasks

- Connect two PCs to a Cisco switch.
- Configure IPv4 addresses.
- Configure a management IP address on the switch.
- Verify connectivity between the PCs.
- Test connectivity using ping.
- Verify the switch configuration.

## Verification

### PC1 → PC2

ping 192.168.1.20

### PC2 → PC1

ping 192.168.1.10

## Skills Demonstrated

- IPv4 addressing
- Subnet masks
- LAN configuration
- Cisco switch basics
- Connectivity testing
- Network troubleshooting

## Tools

- Cisco Packet Tracer
