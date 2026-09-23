# Virtual Machine Inventory

| VM | Role | vCPU | RAM | Disk | OS |
|---|---|---:|---:|---:|---|
| FGT-LAB | FortiGate firewall | 2 | 2 GB | 20 GB | FortiGate VM |
| SW01 | Virtual L2 switch | 1 | 2 GB | 10 GB | Ubuntu Server / Open vSwitch |
| DC01 | Domain Controller | 2 | 5 GB | 60 GB | Windows Server |
| MGMT01 | IT management client | 2 | 4 GB | 50 GB | Windows 11 Pro |
| CLIENT01 | Domain client | 2 | 3 GB | 50 GB | Windows 11 Pro |
| CLIENT02 | Domain client | 2 | 3 GB | 50 GB | Windows 11 Pro |
| GUEST01 | Guest test client | 2 | 2 GB | 30 GB | Windows 11 Pro |

DC01 provides Active Directory, DNS, DHCP and Group Policy services.
