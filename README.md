# Security Log Monitoring & Incident Analysis

## Objective
To detect and analyze failed SSH login attempts using Linux logs.

## Tools Used
- Linux (Ubuntu)
- grep, awk
- SSH
- fail2ban

## Steps Performed
- Installed and configured SSH server
- Simulated brute-force attack using invalid login attempts
- Analyzed /var/log/auth.log for failed login entries
- Identified suspicious activity
- Created incident report

## Outcome
Detected repeated failed login attempts indicating a possible brute-force attack and suggested mitigation strategies.
