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
