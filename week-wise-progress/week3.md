**Day 1 — 14th July, 2026**

Course 3 Module 2 - Network Operations — completed.
Graded challenge completed.

Key takeaways:
- Clarified complex networking concepts using campus analogy:
  - Subnetting/CIDR: dividing a large network into manageable, secure departments.
  - Security Zones (e.g., DMZ): controlled reception areas allowing limited outside access without exposing internal networks.
  - Firewall: security guards checking packets against specific rules.
  - Proxy Server: an intermediary runner that fetches requests to hide internal IP addresses from the outside internet.

OverTheWire Bandit — Levels 10 and 11 completed.

Level 10:
- Goal: Decode base64 text in data.txt
- Command: base64 -d data.txt
- Concept: decoded obfuscated text using built-in linux tools

Level 11:
- Goal: Break ROT13 cipher in data.txt
- Command: cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
- Concept: piped file contents into the translate command to shift the alphabet by 13 characters.

**Day 2 — 15th July, 2026**

Course 3 Module 3 - Secure Against Network Intrusion — in progress.

Completed:
- Introduction to network intrusion tactics (welcome video,
  case for securing networks, how intrusions compromise systems)
- Secure networks against Denial of Service (DoS) attacks section
- Activity: Analyze network layer communication — Grade: 100%
- Test your knowledge: Secure networks against DoS attacks — Grade: 100%

Key takeaways:
- DoS attacks aim to disrupt availability by overwhelming a system
  with traffic or requests, directly tying back to the CIA triad
- tcpdump logs capture raw network traffic and are used to
  identify abnormal patterns during an attack
- Real-life DDoS case studies show how attacks scale across
  distributed sources, making them harder to block than single-source DoS

Remaining in Module 3:
- Network attack tactics and defense (packet sniffing, IP spoofing,
  interception tactics) — not yet started
- Module challenge 3 (graded, 50 min) — pending

Bandit Level 12 — starting now.

**Day 2 — 15th July, 2026**

Course 3 Module 3 - Secure Against Network Intrusion — COMPLETE.

Covered:
- Introduction to network intrusion tactics
- Secure networks against Denial of Service (DoS) attacks
  - Activity: Analyze network layer communication — Grade: 100%
  - Test your knowledge: Secure networks against DoS attacks — Grade: 100%
- Network attack tactics and defense
  - Malicious packet sniffing
  - IP spoofing
  - DoS attack types and prevention methods
  - Activity: Analyzing logs during a DoS attack
- Module challenge 3 completed

Key takeaways:
- Packet sniffing captures traffic passing through a network,
  which attackers use to intercept unencrypted data such as
  credentials or session tokens
- IP spoofing involves forging the source IP address in a packet
  to disguise the attacker's identity or impersonate a trusted host
- DoS attacks come in multiple forms (e.g. flooding, resource
  exhaustion) — prevention relies on rate limiting, firewalls,
  and traffic filtering
- Reviewing logs during a live DoS attack helps identify the
  attack signature (repeated requests, unusual source patterns)
  and supports faster containment

Bandit Level 12 — completed today.


**Day 3 — 16th July, 2026**

Course 3 Module 4 - Security Hardening — in progress.

Completed:
- Introduction to security hardening
- OS hardening
  - Activity: Apply OS hardening techniques — Grade: 100%
  - Test your knowledge: OS hardening — Grade: 100%
- Network hardening
  - Activity: Analysis of network hardening — Grade: 100%
  - Test your knowledge: Network hardening — Grade: 100%

Key takeaways:
- OS hardening reduces attack surface through brute force attack
  prevention, regular patch updates, and encryption using latest
  standards
- Network hardening covers port filtering, network access
  privileges, and encryption over networks
- Some hardening tasks are one-time setup (initial config),
  while others are ongoing — firewall rule maintenance, network
  log analysis, patch updates, and server backups
- Network log analysis = examining logs to identify events of
  interest, tying back to earlier log source concepts (firewall,
  network, server logs)
- Covered core network defense tools: firewalls, IPS (Intrusion
  Prevention Systems), IDS (Intrusion Detection Systems), and
  network segmentation

**Hands-on practice (outside coursework):**
- Used Wireshark to perform packet sniffing on home WiFi network
- Used Ettercap to intercept and view data packets flowing between
  PC and laptop on the same network (MITM-style traffic capture)
- Captured and analyzed the resulting data packets in Wireshark

Key takeaways:
- Wireshark captures live network traffic and breaks it down
  packet-by-packet, showing protocol headers, source/destination
  addresses, and payload data
- Ettercap can position a device between two hosts on a LAN to
  intercept traffic passing between them, demonstrating in practice
  why unencrypted traffic and unsegmented networks are risky
- Direct hands-on reinforcement of network hardening theory covered
  this session — seeing sniffed/intercepted traffic first-hand makes
  the case for encryption and network segmentation concrete
