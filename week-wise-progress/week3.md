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
