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
