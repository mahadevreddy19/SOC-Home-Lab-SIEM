# Sample SIEM Detection Queries

## Failed Login Detection
index=windows EventCode=4625
| stats count by Account_Name
| where count > 5

## PowerShell Execution
index=windows EventCode=4688
| search New_Process_Name="*powershell.exe*"

## Notes
Queries are simplified for learning purposes.
