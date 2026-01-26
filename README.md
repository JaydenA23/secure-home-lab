# Secure Home Lab – Linux & Windows Security (VirtualBox)

This project documents the design, deployment, and hardening of a secure home lab using Linux (Ubuntu) and Windows 11 virtual machines. The lab was built to demonstrate core cybersecurity principles including system hardening, patch management, user privilege control, and endpoint protection.

The goal was to simulate real-world enterprise security practices in a controlled virtual environment and provide clear documentation and validation evidence.

## Tools Used
- Oracle VirtualBox
- Ubuntu Linux (LTS)
- Windows 11 (x64)
- Microsoft Defender Antivirus
- PowerShell
- GitHub (documentation & version control)

## Linux Secure Lab
Configuration
- Ubuntu virtual machine created in VirtualBox
- Allocated system resources (RAM, CPU, disk)
- System fully updated after installation

Security Controls Implemented
- User account configuration following least privilege
- Firewall enabled and verified using UFW
- Regular patching applied via system updates

Outcome
The Linux VM was hardened against basic threats and configured to reflect secure baseline practices commonly used in enterprise environments.

## Windows Secure Lab
Configuration
- Windows 11 virtual machine deployed in VirtualBox
- TPM 2.0 and UEFI enabled to meet Windows 11 security requirements
- Disk encryption configured via VirtualBox
- Networking configured for controlled testing

Security Controls Implemented
- Microsoft Defender real-time protection enabled
- User Account Control (UAC) enforced
- Standard user account created alongside administrator account
- Principle of least privilege demonstrated
- Malware Simulation Test
- EICAR test file used to safely simulate malware
- Microsoft Defender successfully detected and quarantined the threat
- Detection verified via Windows Security protection history

## Key Security Learnings

- Importance of patch management
- Value of least privilege access
- Effectiveness of host-based endpoint protection
- Practical experience troubleshooting security configuration issues
- Importance of documentation and validation evidence


## Key Image evidence
# UFW Configuration on Ubantu Desktop <img width="1919" height="1197" alt="Screenshot 2026-01-01 155722" src="https://github.com/user-attachments/assets/416ffd76-e053-4b9c-adc6-9d22f4728e43" /> 
# Enabled disk encryption (Linux) <img width="1093" height="662" alt="Screenshot 2026-01-08 003325" src="https://github.com/user-attachments/assets/dad90168-3141-433e-b11d-8510fcb4561d" />
# Virus threat and protection enabled (Windows) <img width="1919" height="1197" alt="Screenshot 2026-01-20 235304" src="https://github.com/user-attachments/assets/1a510fbb-4336-4041-89ae-6196736f4fcb" />
# Defender quarintine alert from the Eicar antivirus test <img width="1919" height="1199" alt="Screenshot 2026-01-24 223718" src="https://github.com/user-attachments/assets/cc9af5e3-7bbb-44d6-bd96-c02dca44fb40" />






