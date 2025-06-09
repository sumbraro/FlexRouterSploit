Remote Code Execution in FlexRouter OS < v2.1.8

Vulnerability Description
This vulnerability allows arbitrary code execution through insecure JSON deserialization in the web interface.

Usage
bash
python3 exploit.py
Technical Details
Affected Versions: FlexRouter OS v2.1.7 and below

Attack Vector: Remote/unauthenticated

CVSS Score: 9.8 (Critical)

Disclosure Date: 2024-04-01

Proof of Concept
The exploit demonstrates how to achieve:

Remote command execution

Privilege escalation to root

Persistent backdoor installation

Mitigation
Upgrade to FlexRouter OS v2.1.9 or later immediately.

⚠️ Warning: This repository is for educational purposes only. Do not use against systems you don't own.

Researcher Credits
Discovered by fixcreator
