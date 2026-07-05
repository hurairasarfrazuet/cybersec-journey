# OverTheWire Bandit — Progress Notes

## Level 0
**Goal:** Connect to the Bandit server via SSH
**Command:**
ssh bandit0@bandit.labs.overthewire.org -p 2220
cat readme
**Concept:** SSH connection basics, reading files with cat
**Real world use:** SSH is the primary way security professionals 
connect to remote servers and machines

---

## Level 1
**Goal:** Read a file named `-` in the home directory
**Command:**
cat ./-
**Concept:** Using `./` to reference files with special character 
names that the terminal would otherwise misinterpret as flags
**Real world use:** Attackers and analysts often encounter 
strangely named files on compromised systems

---

## Level 2
**Goal:** Read a file named `spaces in this filename`
**Command:**
cat './--spaces in this filename--'
**Concept:** Handling filenames with spaces using quotes
**Real world use:** Files with unusual names are sometimes used 
to hide data on compromised systems

---

## Level 3
**Goal:** Find a hidden file inside the inhere directory
**Command:**
cd inhere
ls -a
cat ./...Hiding-From-You
**Concept:** Hidden files in Linux start with a dot. 
`ls -la` reveals them while plain `ls` does not
**Real world use:** Malware and attackers frequently hide 
files using dot prefixes to avoid detection

---

## Level 4
**Goal:** Find the only human-readable file in inhere directory
**Command:**
cd inhere
find . -type f -exec file {} + | grep text
cat ./-fileXX
**Concept:** Using `file` command to determine file types 
and `grep` to filter results
**Real world use:** During forensic investigations, analysts 
search through many files to find readable or suspicious ones

---

## Level 5
**Goal:** Find file that is human-readable, 1033 bytes, 
not executable
**Command:**
find . -type f -size 1033c ! -executable -exec file {} + | grep text
**Concept:** Combining multiple conditions in find — 
size, executable status, and file type
**Real world use:** Filtering files by specific properties 
is essential during system investigations

---

## Level 6
**Goal:** Find file owned by user bandit7, group bandit6, 
33 bytes in size — stored somewhere on the server
**Command:**
find / -user bandit7 -group bandit6 -type f 2>/dev/null
**Concept:** 
- Searching entire filesystem with `/` instead of `.`
- `2>/dev/null` redirects error messages to discard them
- stderr (2), stdout (1), stdin (0) are Linux data streams
**Real world use:** On a compromised system, this exact 
pattern is used to hunt for password files, config files, 
and SSH keys while suppressing noise
