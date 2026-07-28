**Day 1 — 23rd July, 2026**

Course 4 Module 3: Navigate the Linux file system — in progress.

Completed:
- Navigate the Linux file system
  - Linux commands via the Bash shell
  - Core commands for navigation and reading files
  - Activity: Find files with Linux commands
  - Test your knowledge: Navigate the Linux file system in Bash
- Manage file content in Bash
  - Filter content in Linux (grep)
  - Activity: Filter with grep
  - Create and modify directories and files
  - Activity: Manage files with Linux commands
  - Test your knowledge: Manage file content in Bash
- Hands-on Linux practice session (applying navigation, file
  reading, and grep filtering directly in the terminal)

Key takeaways:
- Formalized commands already used extensively in Bandit —
  navigation (cd, ls, pwd), reading files (cat, less, head, tail),
  and filtering with grep — now reinforced with structured course
  context rather than trial-and-error
- Creating/modifying files and directories (touch, mkdir, rm, cp,
  mv) covered as a natural extension of navigation and reading
- Strong overlap between coursework and Bandit levels completed
  so far — theory catching up to practice rather than the reverse

**Day 2 — 24th July, 2026**

Course 4 Module 3: Navigate the Linux file system — in progress.

Completed:
- Authenticate and authorize users
  - File permissions and ownership, changing permissions
  - Portfolio Activity: Use Linux commands to manage file
    permissions (graded)
  - Adding and deleting users, responsible use of sudo
  - Test your knowledge: Authenticate and authorize users

Key takeaways:
- File permissions follow the read/write/execute model across
  owner, group, and others — represented numerically (e.g., 755)
  or symbolically (rwxr-xr-x)
- chmod changes permissions, chown changes ownership — both
  central to securing files against unauthorized access
- User management (useradd, userdel, passwd) and sudo control who
  can act as a privileged user — responsible sudo use means only
  escalating privileges when necessary, not working as root by default
- Direct connection to earlier Bandit levels where permission
  checks and file ownership determined which files were readable


**Day 3 — 25th July, 2026**

Course 4 Module 3: Navigate the Linux file system — COMPLETE.
Course 4 Module 4: SQL and Databases — started.

Completed today:
- Get help in Linux (man pages, Linux community resources)
- Test your knowledge: Get help in Linux
- Review: wrap-up, glossary terms
- Module 3 challenge (graded, 50 min)
- Module 4: Introduction to databases section
  - Introduction to databases
  - Query databases with SQL
  - SQL filtering versus Linux filtering
  - Test your knowledge: SQL and databases

Key takeaways:
- Man pages (`man <command>`) provide built-in documentation for
  any Linux command — a core self-help resource for working in
  the shell without leaving the terminal
- Get help in Linux: covered three key commands
  - `man <command>` — opens the full manual page for a command
  - `whatis <command>` — gives a one-line summary of what a
    command does
  - `apropos <keyword>` — searches man page descriptions for a
    keyword, useful when you don't know the exact command name
    but know roughly what you're trying to do
- The Linux community (forums, distro-specific documentation) is
  a key resource when man pages aren't enough
- A database organizes structured data into tables, and SQL
  (Structured Query Language) is used to query, filter, and
  manage that data
- SQL filtering (WHERE clauses) achieves conceptually similar
  goals to Linux filtering (grep) — narrowing down large datasets
  to what's relevant — but operates on structured tables rather
  than plain text/files

**Module 3 complete.** Covers full Linux file system navigation,
content management, permissions, user administration, and getting
help — directly reinforced by ongoing Bandit practice.

**Module 4 started** — new territory (SQL), first real shift away
from command-line/Linux-only content in this course.


**Day 4 — 26th July, 2026**

Course 4 Module 4: SQL and Databases — in progress.

Completed:
- SQL queries
  - Basic queries, running a query against a database
  - Activity: Perform a SQL query
  - Test your knowledge: SQL queries
- More SQL filters
  - Filtering dates and numbers
  - Filters with AND, OR, and NOT
  - Portfolio Activity: Apply filters to SQL queries (graded)
  - Test your knowledge: More SQL filters

Key takeaways:
- SQL queries follow a SELECT ... FROM ... WHERE structure to
  pull specific data from a table
- The WHERE clause filters rows based on conditions — comparable
  in purpose to grep filtering text, but operating on structured
  columns/rows instead of raw text
- Date and number filters use comparison operators (>, <, =, BETWEEN)
  to narrow results by ranges
- AND/OR/NOT combine or exclude multiple conditions in a single
  query — AND narrows (all conditions true), OR broadens (any
  condition true), NOT excludes matches

Remaining in Module 4:
- SQL joins (types of joins, Activity: Complete a join, Test your
  knowledge: SQL joins)
- Review: coach dialogue, wrap-up, glossary, Module 4 challenge
  (graded, 50 min) — completes Course 4

  **Day 6 — 28th July, 2026**

Course 5 Module 1: Introduction to Asset Security — COMPLETE.

Completed today:
- What, Why, and How of cybersecurity (assets, threats, vulnerabilities)
- Risk = Likelihood × Impact; security teams focus on reducing attack surface
- Categories of threats: intentional vs. unintentional
- Categories of vulnerabilities: technical vs. human
- Security plans: policies, standards, procedures
- NIST CSF: three components (core, tiers, profile); six core functions (govern, identify, protect, detect, respond, recover)
- CISA's implementation guidance for the NIST CSF

Key takeaways:
- Risk sits at the intersection of threat and vulnerability — assets define *what* is protected, threats explain *why* protection is needed, and lowering vulnerability is *how* risk gets reduced
- Threats split into intentional (malicious actors) and unintentional (human error) categories; vulnerabilities split into technical (misconfigurations) and human (lost access cards) — either path can escalate into risk
- The NIST CSF profile works like a progress snapshot — comparing current security posture against an earlier point in time, similar to tracking a tree's growth
- CISA's four-step approach (build a profile → risk assessment → gap analysis → plan of action) turns an otherwise abstract framework into something concrete to act on

Next: Course 5 Module 2 (Protect organizational assets).
