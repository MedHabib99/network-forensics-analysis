# Network Forensics Incident Analysis

Security analysis project focused on network forensics and incident investigation.

## Overview

This project analyzes a simulated airport security incident using PCAP captures and log files. The objective was to investigate suspicious VPN activity, reconstruct the attack timeline, and analyze possible exploitation behavior.

## Topics Covered

- PCAP analysis with Wireshark
- VPN log investigation
- SMB/DCERPC traffic analysis
- TLS traffic analysis
- Timeline reconstruction
- Hash verification and chain of custody
- Incident investigation methodology

## Tools Used

- Wireshark
- Linux / Parrot OS
- grep
- SHA-256 hashing

## Key Findings

- Analysis of suspicious SMB/DCERPC traffic
- Investigation of possible EternalBlue-related activity
- Reconstruction of VPN attack timeline
- Identification of suspicious TLS communication
- Correlation of PCAP and log evidence

## Documentation

- [Forensics Report](docs/Airport-Forensics-Report.pdf)
- [Lab Instructions](docs/Lab-Instructions.pdf)
- [ENISA Training Material](docs/ENISA-Training-Material.pdf)

## Screenshots

### VPN Log Analysis
![VPN Analysis](screenshots/vpn-log-analysis.png)

### SMB Traffic Investigation
![SMB Traffic](screenshots/wireshark-smb-traffic.png)

### Suspicious Network Activity
![Suspicious Traffic](screenshots/suspicious-network-traffic.png)

### Attack Timeline Reconstruction
![Timeline](screenshots/attack-timeline-analysis.png)

## Note

This project was completed as part of university coursework using a simulated incident scenario provided for educational purposes.