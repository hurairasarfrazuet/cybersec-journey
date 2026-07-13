## Week 2

**Day 1 - 5th July, 2026**

Course 2 Module 2 sections completed — Security Frameworks 
and Controls, CIA Triad, NIST CSF.

Key takeaways:
- Security frameworks are guidelines for building plans to 
  mitigate risks and threats including social engineering 
  and ransomware
- People are the biggest threat to security - frameworks help 
  build employee awareness
- Security controls are safeguards designed to reduce specific 
  risks. Three common types: encryption, authentication, 
  authorization
- MFA adds an extra layer of authentication beyond just a password
- Authorization = verifying a person has permission to access 
  a resource
- NIST CSF 6 functions: Govern, Identify, Protect, Detect, 
  Respond, Recover
- CIA Triad real world example:
  - Confidentiality: another student viewing my private uni records
  - Integrity: that student changing my marks, data can't be trusted
  - Availability: student changing my permissions so I can't access 
    my own information

OverTheWire Bandit — Levels 3 to 6 completed.
- Level 3: Finding hidden files using ls -la
- Level 4: Identifying human-readable files using file command 
  and grep
- Level 5: Combining multiple find conditions - size, executable 
  status, file type
- Level 6: Searching entire filesystem with /, suppressing errors 
  using 2>/dev/null
- Learned about Linux data streams: stdin (0), stdout (1), 
  stderr (2)
- Connected find commands to real pentesting use cases — hunting 
  for passwords, config files, and SSH keys on compromised systems

Bandit notes documented in bandit-notes.md


**Day 2 — 7th July, 2026**

Course 2 Module 2 completed — OWASP Principles and Security Audit.

OWASP Principles covered:
- Minimize attack surface area — reduce all potential vulnerabilities 
  and pathways attackers could exploit
- Least privilege — users get minimum access needed for their role
- Defense in depth — multiple layered security controls (MFA, 
  firewalls, IDS, permissions)
- Separation of duties — no single person should have enough 
  privileges to misuse the system
- Keep security simple — avoid unnecessarily complicated solutions 
  that become unmanageable
- Fix security issues correctly — identify root cause, fix 
  vulnerabilities, test repairs

Portfolio Activity — Botium Toys Security Audit completed.
Conducted a full controls and compliance assessment for a fictional 
company including:
- Controls assessment: identified missing controls including least 
  privilege, encryption, IDS, backups, disaster recovery plans
- Compliance assessment: PCI DSS, GDPR, SOC — identified gaps 
  in data protection and access management
- Recommendations: enforce least privilege, implement encryption, 
  deploy IDS, establish backup and disaster recovery plans, 
  ensure regulatory compliance for international expansion

Note: Concepts are being retained well. Listed recall improves 
with reference triggers — normal at this stage of learning.


**Day 3 — 9th July, 2026**

Course 2 Module 3 completed — Introduction to Cybersecurity Tools.
Graded challenge score: 93.75%. Submitted before deadline.

OverTheWire Bandit — Levels 7 and 8 completed.

Level 7:
- Goal: Find password next to the word "millionth" in data.txt
- Command: grep millionth data.txt
- Concept: grep searches file contents for specific patterns
- Real world use: Hunting through log files for suspicious 
  activity, failed logins, or specific IP addresses

Level 8:
- Goal: Find the password that appears only once in data.txt
- Command: sort data.txt | uniq -u
- Concept: sort groups identical lines, uniq -u shows only 
  lines appearing exactly once. Must sort before uniq.
- Real world use: Finding unique anomalous events among 
  thousands of repeated log entries

Key takeaways:
- Three common log sources:
  - Firewall logs: incoming/outgoing connection attempts
  - Network logs: devices entering/leaving network, 
    connections between services
  - Server logs: events related to websites, emails, 
    file shares including login and username requests
- SIEM tools centralize, analyze and visualize log data 
  from multiple sources
- SIEM dashboards provide visual representations of 
  security events and metrics like response time, 
  availability, and failure rate
- Metrics help stakeholders assess performance of 
  security systems
- Connected SIEM outage scenario directly to CIA triad — 
  outage = Availability violation
- SIEM tools can support automated response actions 
  like blocking suspicious IPs

Note: Starting to connect concepts across topics naturally 
rather than treating them in isolation.

**Day 4 — 10th July, 2026**

Course 2 - Play It Safe: Manage Security Risks — COMPLETE.
Module 4 graded challenge score: 100%.

Key takeaways:
- Incident response is an organization's quick attempt to 
  identify, contain, and correct the effects of a security breach
- Incident Response Playbook has 6 phases:
  1. Preparation - documenting procedures, staffing plans, 
     user education
  2. Detection and Analysis - detect and analyze events using 
     defined processes and technology
  3. Containment - prevent further damage and reduce immediate 
     impact
  4. Eradication and Recovery - remove malicious code, mitigate 
     vulnerabilities, restore environment to secure state
  5. Post-Incident Activity - document incident, inform leadership, 
     apply lessons learned
  6. Coordination - report incidents and share information 
     throughout the response process

Bandit: Levels 7 and 8 complete. Level 9 postponed to tomorrow.

**Day 5 — 11th July, 2026**

Course 3 started — Connect and Protect: Networks and 
Network Security.
Module 1 - Network Architecture — sections 1 and 2 completed.

Key takeaways:
- Network: collection of devices connected through a medium 
  to communicate. Types: LAN and WAN
- Hub: sends packets to all connected devices
- Switch: smart enough to send packets to destination device 
  only — improves performance
- Router: connects multiple networks together
- TCP/IP model 4 layers: Network Access, Internet, 
  Transport, Application
- OSI model: 7 layer theoretical framework used for 
  troubleshooting — more granular than TCP/IP
- IP address: logical address that can change, gets data 
  to the right network (IPv4 and IPv6)
- MAC address: permanent hardware ID burned into NIC, 
  gets data to the right device within a network
- MAC can be spoofed, IP can be traced — both critical 
  concepts in offensive and defensive security

TryHackMe - Linux Fundamentals Part 1 completed (free room).
- Covered core commands: ls, cd, cat, grep, find
- Operators: & (background), && (chain if success), 
  > (overwrite), >> (append)
- Formally reinforced commands already practiced on Bandit — 
  practical experience first, theory second

Bandit Level 9 — pending, tomorrow priority.

Also completed: Python for Everybody Course 1 
(University of Michigan, Coursera) — ahead of roadmap schedule.


**Day 6 — 12th July, 2026**

Course 3 Module 1 - Network Architecture — fully completed.
Graded challenge: 100% (3rd attempt — learned to read 
questions carefully instead of skimming).

Key takeaways:
- LAN: local network within one building/organization
- WAN: wide area network spanning large geographic distances, 
  internet is the largest WAN
- TCP/IP 4 layers and their roles:
  - Application: prepares data from user applications
  - Transport: breaks data into segments, adds port numbers, 
    ensures reliable delivery
  - Internet: adds IP addresses, handles routing between networks
  - Network Access: physical transmission, adds MAC addresses
- Public IP: assigned by ISP, shared by all devices on same 
  network via router translation (NAT)
- Private IP ranges: 10.0.0.0, 172.16.0.0, 192.168.0.0
- MAC address: permanent hardware ID, used for device 
  identification within local network
- MAC can be spoofed, used in ARP poisoning attacks

OverTheWire Bandit - Level 9 completed.
- Command: strings data.txt | grep '='
- strings extracts human readable content from binary files
- ^ anchor in regex means "starts with" — removing it 
  matches pattern anywhere in line
- Real world use: extracting readable content from binary 
  files during forensic investigation


**Day 7 — 13th July, 2026**

Course 3 Module 2 - Network Operations — partially completed.
Covered up to security zones section.

Key concepts encountered:
- Network protocols and their roles across TCP/IP layers
- DNS, HTTP/HTTPS, TCP, UDP, IP, ARP, ICMP protocols
- Each protocol is a potential attack surface:
  - DNS spoofing, ARP poisoning, SYN floods, ICMP ping sweeps
- Started security zones section

Note: Module 2 is significantly denser than previous modules.
Continuing tomorrow.

Bandit Level 10 — pending tomorrow.
