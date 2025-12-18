# Incident Report – Brute Force Detection

## Summary
An alert was generated for multiple failed login attempts
followed by a successful authentication.

## Investigation
- Reviewed Windows Event IDs 4625 and 4624
- Identified repeated failed attempts from same source
- Verified account activity and timestamps

## MITRE ATT&CK
- T1110 – Brute Force

## Response
- Account password reset
- Monitored for further suspicious activity
