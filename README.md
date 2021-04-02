# RedvsBlue
Full Red vs Blue activity performing both penetration testing and security monitoring.

The activities performed in this exercise are intended to replicate a Red vs Blue engagement. As a small group we initially played the role of a blackhat hacker gaining unauthorized access to a company web server and utilizing a PHP reverse shell to establish a Meterpreter session allowing for exfiltration of company data. We then performed the role of a Blue Team analyzing the Kibana logs to summarize the incident before making system hardening recommendations. By performing all of the roles, this exercise gave us good insight into both offensive and defensive security roles.

This repository contains a readout of this activity containing the following details:
- Network Topology 
- Network Reconnaissance
- Vulnerability Assessment
- Exploit summary
- Incident Analysis
- Mitigation Strategies

An diagram of the Network Topology can be found here:

https://github.com/mtslutz/RedvsBlue/blob/main/images/Network%20Topology.png

The configuration details of each machine may be found below:

| Name                 | Function   | IP Address    | Operating System |
|----------------------|------------|---------------|------------------|
| Hypervisor           | Hypervisor | 192.168.1.1   | Windows          |
| Kali                 | Attack VM  | 192.168.1.90  | Kali Linux       |
| Capstone             | Target VM  | 192.168.1.105 | Ubuntu Linux     |
| ELK                  | Logging    | 192.168.1.100 | Ubutnu Linux     |
