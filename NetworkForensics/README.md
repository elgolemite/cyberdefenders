# Network Forensics Challenge Summary

| Challenge Name | Brief Description |
|---|---|
| Web Investigation Lab | Investigates a web-server compromise involving SQL injection against a vulnerable PHP search page. The analysis identifies the attacker’s IP and location, reconstructs the SQL injection timeline, determines the exposed database table, discovers an administrative directory, recovers login credentials, and identifies an uploaded PHP web shell. |
| XLMRat Lab | Examines malware delivery and execution through HTTP traffic. The investigation extracts embedded payloads from a malicious script, calculates their hashes, identifies the malware family as AsyncRAT, determines the sample’s creation time, discovers the RegSvcs.exe LOLBin used for execution, and lists the files dropped by the script. |
| DanaBot Lab | Analyses a DanaBot infection that begins with a malicious JavaScript file downloaded through HTTP. The investigation identifies the attacker IP, extracts and hashes the initial payload, determines that wscript.exe executes the JavaScript, and extracts a secondary DLL payload for further malware analysis. |
| PsExec Lab | Investigates lateral movement performed with PsExec over SMB. The analysis identifies the compromised machines, attacker account, PsExec service executable, ADMIN$ share used to transfer the service, IPC$ share used for communication, and the hostnames of the first and second compromised systems. |
| Tomcat Takeover Lab | Investigates the compromise of an Apache Tomcat server. The attacker scans the target, enumerates Tomcat directories using Gobuster, discovers the `/manager` administration panel, brute-forces its credentials, uploads a malicious WAR file, establishes a reverse shell, and creates a cron job for persistence. |
