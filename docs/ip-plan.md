# IP Plan

All addresses below are private RFC1918 addresses used in the virtual laboratory.

| VLAN | Name | Network | Gateway | Example device |
|---|---|---|---|---|
| 10 | MANAGEMENT | 10.10.10.0/24 | 10.10.10.1 | MGMT01: 10.10.10.10 |
| 20 | SERVERS | 10.10.20.0/24 | 10.10.20.1 | DC01: 10.10.20.10 |
| 30 | USERS | 10.10.30.0/24 | 10.10.30.1 | CLIENT01/CLIENT02 via DHCP |
| 40 | DMZ | 10.10.40.0/24 | 10.10.40.1 | Reserved for services |
| 50 | GUEST | 10.10.50.0/24 | 10.10.50.1 | GUEST01 via DHCP |
| 99 | NATIVE/BLACKHOLE | 10.10.99.0/24 | — | Unused |

FortiGate provides the VLAN gateway interfaces and controls traffic between segments.
Domain clients use the domain controller as their DNS server.
