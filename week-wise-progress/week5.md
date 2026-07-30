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
