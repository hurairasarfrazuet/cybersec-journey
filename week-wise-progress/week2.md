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
