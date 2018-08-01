# Data Collection
Our data collection consists of full traffic capture for all VLANs pertaining to the department network infrastructure, namely LAN1 through LAN4, FWVR0, FWVR1, FWVR2 (virtual routers and firewall), as well as the service lans CED, DMZ INT and DMZ EXT.
## Traffic captured
The capturing period started at 14:30 on 25 July 2018 and continuously ran for an exact duration of 4 days, ending at 14:30 on 29 July 2018. Overall, the dataset contains the following information with the relative links to download.
### Full daily captures
One PCAP file per day with the full capture for each VLAN:
* [25 July 2018] (link) - Wednesday full day capture
* [26 July 2018] (link) - Thursday full day capture
* [27 July 2018] (link) - Friday full day capture
* [28 July 2018] (link) - Saturday full day capture
* [29 July 2018] (link) - Sunday full day capture
### Attacks captures
A separated PCAP files for each attack:
* [Heartbleed] (link) - Heartbleed attack that involved the attacker 1.2.3.3 and victim 200.100.0.8
* [Bruteforce] (link) - Bruteforce attack that involved the attacker 1.2.3.3 and victim 200.100.0.3
* [Web Application Attack] (link) - Web Application Attack (Drupal) attack that involved the attacker 1.2.3.16 and victim 200.100.0.3
* [LAN Attack + Ransomware Deployment:] (link) - LAN Attack + Ransomware Deployment that involved the attacker 10.1.10.2 and victim 10.1.12.2
* [PortScan] (link) - PortScan attack that involved the attacker 1.2.3.3 and LAN4
### Benign traffic captures
A separate PCAP file with all traffic from LAN1-LAN2 for 26/07, containing only benign (agentrelated) flows:
* [WEB 9:00 18:30 ] (link) - WEB traffic from 9:00 to 18:30 with frequency 15 minutes from all hosts to Web
### Features
For each PCAP file, a CSV files containing, for each extracted flow, the values for 80 traffic related features.
* [WEB 9:00 18:30 ] (link) - 
