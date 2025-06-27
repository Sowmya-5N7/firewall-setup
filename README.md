# Firewall Setup and Testing on Windows

## Objective
Configure and test basic firewall rules to control network traffic by allowing or blocking specific ports/services on Windows (Windows Firewall).

### Key Takeaways
-  Understand how firewalls filter incoming/outgoing traffic.
-  Practice creating, modifying, and deleting firewall rules.
-  Verify rules by testing blocked/allowed connections (e.g., Telnet).

## Tools Used
-  Windows Defender Firewall Advanced Security
-  Powershell

## Windows Implementation
### Enabling Telnet Client (Testing Tool)
-  Validate firewall rule effectiveness
-  Test port blocking/allowing functionality
-  Demonstrate insecure protocol behavior (educational context)

### Command
dism /online /Enable-Feature /FeatureName:TelnetClient
