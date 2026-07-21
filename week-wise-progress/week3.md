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


**Day 4 — 17th July, 2026**

Course 3 Module 4 - Security Hardening — COMPLETE.
Course 3 - Connect and Protect: Networks and Network Security — COMPLETE.

Completed today:
- Cloud hardening (network security in the cloud, cryptography
  and cloud security, test your knowledge)
- Review: Coach dialogue on reinforcing system hardening and
  vulnerability defense, wrap-up, glossary terms
- Module 4 challenge (graded)
- Portfolio activity: Use the NIST Cybersecurity Framework to
  respond to a security incident (graded)

Key takeaways:
- Cloud hardening extends the same hardening principles (access
  control, encryption, monitoring) to cloud-hosted infrastructure,
  with added focus on cloud-specific misconfigurations
- Cryptography plays a central role in cloud security — encrypting
  data at rest and in transit across cloud services
- Applied the NIST CSF (Govern, Identify, Protect, Detect, Respond,
  Recover) in a practical portfolio scenario, mapping each function
  to concrete response actions during a simulated security incident
- Full module tied together OS, network, and cloud hardening as
  layered defense — reinforcing the "defense in depth" principle
  from earlier OWASP coverage

**Course 3 complete.** Covers network architecture, protocols,
network operations, security zones, DoS/intrusion defense, and
full-spectrum hardening (OS, network, cloud). Next: Course 4.

**Self-Review Quiz — Course 3 Full Review (Scenario-Based)**

Tested understanding across 4 scenario-based questions covering
the full span of Course 3:

1. **Network Architecture** — Correctly identified a same-subnet
   connectivity issue as a switch-level problem, not a routing
   issue, based on where switches vs. routers operate.
2. **DoS vs. DDoS** — Correctly identified a multi-source attack
   as DDoS and explained why distributed sources make detection
   and IP-blocking far harder for defenders.
3. **Packet Sniffing & Encryption** — Correctly identified HTTP
   traffic as readable in plaintext vs. HTTPS traffic protected by
   SSL/TLS encryption. Also independently identified that metadata
   (source/destination IPs, packet timing/size) still leaks even
   over encrypted connections.
4. **Incident Response** — Correctly identified isolating infected
   machines as the Containment phase, and explained why it's kept
   separate from Eradication/Recovery (stopping spread immediately
   vs. thorough cleanup afterward).

Result: 4/4 correct, with solid reasoning rather than just recall —
particularly strong on connecting concepts across modules (e.g.
tying encryption back to earlier network hardening, tying Ettercap/
Wireshark hands-on practice back to real packet sniffing risk).

**Day 5 — 20th July, 2026**

Course 4 - Tools of the Trade: Linux and SQL — started.
Module 1: The wonderful world of operating systems — COMPLETE.

Covered:
- Course 4 overview and orientation
- Introduction to operating systems, comparing OS types
- How the OS handles requests and allocates resources
- Virtualization technology
- GUI vs CLI
- Module 1 challenge

Key takeaways:
- An operating system manages hardware resources and mediates
  requests between applications and hardware (CPU, memory, storage)
- Virtualization allows a single physical machine to run multiple
  isolated operating systems — directly relevant to my Kali Linux
  VM setup on VirtualBox
- GUI vs CLI: GUI relies on visual elements for interaction, CLI
  relies on typed commands — CLI offers more precision and
  automation potential, which is why it's central to security work
- Connected virtualization theory directly to my own lab setup
  (Kali VM + Windows VM on VirtualBox)

  **Day — 21st July, 2026**

Course 4 Module 2: The Linux operating system — in progress.

Completed:
- All about Linux (introduction, Linux architecture)
  - Test your knowledge: All about Linux — Grade: 100%
- Linux distributions (overview, Kali Linux, package managers,
  lab resources and troubleshooting tips)
  - Activity: Install software in a Linux distribution
  - Test your knowledge: Linux distributions — Grade: 100%

Key takeaways:
- Linux architecture layered top to bottom: applications → shell
  (interface to interact with the OS) → kernel (core, manages
  hardware/resources) → hardware
- Two major distro families:
  - **Debian-based**: Ubuntu, Kali, Parrot, Tails
  - **Red Hat-based**: Red Hat itself
- Package management differs by family:
  - Debian family uses `dpkg` as the underlying package manager,
    with `apt` as the higher-level management system
  - Red Hat family uses `rpm` as the underlying package manager,
    with `yum` as the higher-level management system
- Directly applicable since my own Kali VM is Debian-based —
  meaning `apt`/`dpkg` are the tools I'll actually be using
