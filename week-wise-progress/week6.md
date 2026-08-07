**Week 6, Day 1 — 7th August, 2026**

Course 6 Module 2: Network Monitoring and Analysis — IN PROGRESS (nearly complete).

Completed today:
- Understanding network traffic
  - The importance of network traffic flows
  - Maintain awareness with network monitoring
  - Data exfiltration attacks
  - Test your knowledge: Understand network traffic (Graded — 100%)
- Capture and view network traffic
  - Packets and packet captures
  - Interpret network communications with packets
  - Reexamine the fields of a packet header
  - Investigate packet details
  - Activity: Analyze your first packet
  - Test your knowledge: Capture and view network traffic (Graded — 100%)

Remaining in Module 2: packet inspection section and the module wrap-up.

Hands-on practice (PortSwigger Web Security Academy):
- Practiced SQL injection labs, successfully gaining access on two lab websites

Key takeaways:
- Network monitoring can be automated (IDS watching packet payloads for known attack patterns) or manual (packet sniffers like tcpdump/Wireshark, used to capture and inspect traffic in detail) — both matter because automated tools catch known patterns while manual inspection catches what automation misses or misclassifies
- Data exfiltration is a traffic-pattern problem as much as a content problem — unusual outbound volume or destinations can flag an exfiltration attempt even before payload inspection confirms it
- A packet capture isn't just "traffic" — headers carry the metadata (source/destination, protocol, flags) that lets an analyst reconstruct what actually happened in a conversation between two systems
- SQL injection in practice reinforces the Course 5 theory directly — exploiting insufficient input sanitization to manipulate a database query and bypass intended access controls

Next: Finish Course 6 Module 2 (packet inspection, wrap-up); continue PortSwigger SQLi labs.
