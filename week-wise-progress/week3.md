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
