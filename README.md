# Task 4 — Firewall Configuration (Windows)

## 🔹 Objective
Configure and test basic firewall rules to allow or block network traffic.

## 🔹 Tool Used
- Windows Defender Firewall with Advanced Security (Windows 10/11)

## 🔹 Steps Performed
1. Opened Windows Defender Firewall with Advanced Security.
2. Viewed existing inbound rules.
3. Created a new rule to **block Telnet (TCP port 23)**:
   - Rule Type: Port  
   - Protocol: TCP  
   - Port: 23  
   - Action: Block connection  
   - Profiles: Domain, Private, Public  
   - Rule Name: *Block Telnet Port 23 (Test Rule)*
4. Verified the rule was applied successfully.
5. Removed the rule to restore the firewall’s default state.

## 🔹 Observations
- The firewall rule blocked inbound Telnet connections.
- The test rule was later removed, restoring the system configuration.

## 🔹 Conclusion
This task showed how a firewall filters traffic based on defined rules.  
By blocking Telnet (port 23), insecure communication was prevented, proving how firewall rules strengthen system security.
