# Security Architecture

## Network Segmentation

The network is separated into management, server, user, DMZ and guest VLANs.

## Firewall

FortiGate is used as the central Layer-3 gateway and firewall. Inter-VLAN communication is controlled through explicit policies.

## Guest Isolation

The guest network is designed to provide external access while preventing access to internal resources such as the domain controller and other internal services.

## File Transfer

OpenSSH/SFTP is used for controlled file transfer. Separate permissions were tested for read-only and read-write users.

## Mail Security

Postfix and Dovecot were configured for SMTP/IMAP services. TLS connectivity and open-relay protection were tested.

## Integrity

SHA-256 hashes were used to verify backup/file integrity.

## Evidence

Test evidence is available under `screenshots/`.
