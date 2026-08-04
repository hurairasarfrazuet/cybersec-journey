**Week 5, Day 1 — 30th July, 2026**

Course 5 Module 2: Protect Organizational Assets — COMPLETE.

Completed today:
- Encryption methods
  - Fundamentals of cryptography
  - Public key infrastructure
  - Symmetric and asymmetric encryption
  - Resources for completing labs; lab tips and troubleshooting steps
  - Activity: Decrypt an encrypted message
  - Non-repudiation and hashing
  - The evolution of hash functions
  - Activity: Create hash values
  - Test your knowledge: Encryption methods (Graded — 100%)
- Authentication, authorization, and accounting
  - Access controls and authentication systems (basic auth, OAuth, API tokens, session cookies)
  - The rise of SSO and MFA
  - The mechanisms of authorization
  - Why we audit user activity
  - Identity and access management
  - Activity: Improve authentication, authorization, and accounting for a small business (Graded — 100%)
  - Test your knowledge: Authentication, authorization, and accounting (Graded — 100%)
- Review: Protect organizational assets
  - Wrap-up, glossary terms
  - Module 2 challenge (Graded — 95%)

Key takeaways:
- Symmetric encryption is faster but requires securely sharing a single key; asymmetric encryption solves the key-distribution problem using public/private key pairs, at the cost of speed — PKI ties public keys to verified identities via certificates
- Hashing provides integrity and non-repudiation — a hash proves data hasn't changed, but unlike encryption it can't be reversed back to the original data
- Authentication (proving identity), authorization (defining what an identity can access), and accounting (logging what was done) form the AAA model — auditing exists specifically to make actions traceable after the fact
- SSO and MFA both reduce risk from credential-based attacks, but for different reasons: SSO reduces password sprawl and reuse, while MFA adds a second independent barrier even if a password is compromised
- Different auth mechanisms (basic auth, OAuth, API tokens, session cookies) trade off differently between statelessness, security, and convenience depending on the system's needs

Next: Course 5 Module 3 (Vulnerabilities in systems).


**Week 5, Day 2 — 1st August, 2026**

Course 5 Module 3: Vulnerabilities in Systems — IN PROGRESS.

Completed today:
- Vulnerability management (intro) and vulnerabilities of CI/CD
- Defense in depth strategy
- Common vulnerabilities and exposures (CVE)
- The OWASP Top 10
- Open source intelligence (OSINT)
- Test your knowledge: Flaws in the system (Graded — 100%)
- Vulnerability assessments
- Approaches to vulnerability scanning
- The importance of updates
- Penetration testing (intro to the career path)
- Test your knowledge: Identify system vulnerabilities (Graded — 100%)
- Portfolio Activity: Analyze a vulnerable system for a small business (Graded — 100%)

Key takeaways:
- Defense in depth is a layered model (perimeter, network, endpoint, application, data) — like a castle's moat, walls, watchtowers, inner defenses, and treasure room, so a breach at one layer doesn't expose everything
- Vulnerability assessment follows a repeatable cycle: identification → analysis (root cause) → risk assessment (likelihood × impact) → remediation
- Vulnerability scanning has real trade-offs: external vs. internal (attacker's view vs. inside-the-network view), authenticated vs. unauthenticated (credentialed depth vs. outsider realism), and limited vs. comprehensive (speed vs. coverage)
- Penetration testing draws on nearly everything covered so far — networking, Linux, vulnerability analysis, and scripting — reinforcing that this roadmap's breadth is intentional, not scattered
- Bug bounty programs (e.g. HackerOne) are a legitimate, structured way for freelance and amateur security professionals to practice pen testing skills for real rewards

Remaining in Module 3: vulnerability scanning types in more depth, wrap-up, and the Module 3 challenge.

Next: Continue Module 3.


**Week 5, Day 3 — 2nd August, 2026**

Course 5 Module 3: Vulnerabilities in Systems — COMPLETE.

Completed today:
- Cyber attacker mindset
  - Protect all entry points
  - Approach cybersecurity with an attacker mindset
  - Types of threat actors
  - Pathways through defenses
  - Self-reflection: Approach cybersecurity with an attacker mindset (Graded — 100%)
  - Fortify against brute force cyber attacks
  - Activity: Identify the attack vectors of a USB drive (Graded — 100%)
  - Test your knowledge: Cyber attacker mindset (Graded — 100%)
- Review: Vulnerabilities in systems
  - Wrap-up, glossary terms
  - Module 3 challenge (Graded — 90%)

Key takeaways:
- Thinking like an attacker means treating every entry point — physical, digital, even a dropped USB drive — as a potential pathway in, not just the obvious network-facing ones
- Threat actors vary widely (script kiddies, hacktivists, insider threats, nation-states, organized crime, etc.), and their motives shape which assets they target and how
- Brute forcing is a numbers game attackers automate rather than do by hand — tools like Aircrack-ng, Hashcat, John the Ripper, Ophcrack, and THC Hydra each specialize in different attack surfaces (Wi-Fi, password hashes, etc.), and security professionals use the same tools defensively to test their own systems
- A dropped USB drive is a classic social engineering vector — the exploit isn't technical at all, it relies on human curiosity to bypass every technical control in place

**Course 5, Module 3 complete.** Covered the full vulnerability management lifecycle — CVE, OWASP Top 10, OSINT, vulnerability assessments and scanning, penetration testing fundamentals — capped off with building the attacker mindset needed to actually think through how those vulnerabilities get exploited in practice.

Next: Course 5 Module 4 (Threats to asset security).


**Week 5, Day 4 — 4th August, 2026**

Course 5 Module 4: Threats to Asset Security — IN PROGRESS.

Completed today:
- Social engineering
  - The criminal art of persuasion
  - Social engineering tactics
  - Phishing for information
  - Types of phishing
  - Test your knowledge: Social engineering (Graded — 100%)
  - Activity: Filter malicious emails (Graded — 100%)
- Malicious software
  - An introduction to malware
  - The rise of cryptojacking
  - Test your knowledge: Malware (Graded — 100%)
- Web-based exploits
  - Cross-site scripting (XSS)
  - Exploitable gaps in databases
  - Prevent injection attacks
  - Test your knowledge: Web-based exploits (Graded — 100%)

Key takeaways:
- Social engineering succeeds by exploiting human psychology (urgency, authority, trust) rather than technical flaws — phishing has several distinct forms (spear phishing, whaling, vishing, smishing) each targeting the same weakness through a different channel
- Malware isn't one thing — cryptojacking specifically hijacks a victim's processing power for mining rather than stealing data outright, showing that not every compromise is about data theft
- XSS attacks inject malicious scripts that run in a victim's browser via a trusted site, while injection attacks (like SQL injection) target the database layer directly — both stem from the same root problem: failing to properly validate or sanitize user input
- Prevention for injection-style attacks centers on input validation and sanitization — treating anything a user submits as untrusted until proven otherwise

Remaining in Module 4: further threat topics, wrap-up, and the Module 4 challenge (final module of Course 5).

Next: Continue Module 4.
