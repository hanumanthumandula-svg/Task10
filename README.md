# Task-10-Firewall-Configuration-Testing
**# objective**

Configure and test firewall rules using UFW to control network traffic and improve system security.

**# Tools Used**

UFW (Uncomplicated Firewall)
Nmap
iptables

**# Steps Performed**

Enabled UFW and set default policies (deny incoming, allow outgoing).
Allowed SSH (22), HTTP (80), and HTTPS (443).
Blocked port 8080.
Blocked malicious IP: 192.168.1.100.
Allowed trusted IP: 192.168.1.50.
Tested rules using Nmap.
Enabled firewall logging.
Verified rules using iptables.

**# Observations**

Allowed ports appeared filtered externally due to firewall rules.
Blocked ports and IPs were inaccessible.
Logs confirmed firewall actions.

**# Final Outcome**

Hands-on firewall management and testing skills.
