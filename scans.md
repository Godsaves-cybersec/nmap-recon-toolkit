
---

scans.md 


Example:

 Nmap Scan Results

 Target: 192.168.191.130

Command Used:
```bash
nmap -sV 192.168.191.130
Results:
Port 22: SSH (Open)
Port 80: HTTP (Open)
Port 443: HTTPS (Open)
Target: 192.168.191.130
Command Used:
nmap -A 192.168.191.130
Findings:
Linux OS detected
Apache web server running
SSH enabled

Observations
- SSH service exposed (potential attack surface)
- Web server running (needs vulnerability testing)
- HTTPS enabled (secure communication present)

---

 Risk Level
Medium (based on exposed services)

---

 Recommendations
- Restrict SSH access using firewall rules
- Perform web vulnerability testing (Burp Suite)
- Disable unused services



