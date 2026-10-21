# Nishant Carvalho — IT Support → Security Operations
Melbourne, AU · Master of Cybersecurity (Swinburne)

Building blue-team labs: SIEM detections, AD attack/detect, cloud security.

**Certs:** Splunk SODA · Qualys VMDR · AWS Cloud Practitioner (in progress)

## Labs

**[Lab 01: Linux Server Hardening (CIS)](https://github.com/carvalhonishant/lab-01-linux-hardening-cis)**
Baselined and hardened an Ubuntu server with Lynis (hardening index 61 to 75), added auditd rules and AIDE file integrity monitoring, and wrote a Bash script that checks 14 CIS style controls. Built on an isolated home lab with before and after evidence.

**[Lab 02: macOS Hardening and Log Analysis](https://github.com/carvalhonishant/lab-02-macos-hardening-logging)**
Hardened a managed macOS endpoint (FileVault, application firewall, stealth mode) and wrote a Bash tool to triage the unified log for high signal events. Each hardening change is proven in the system's own logs.

**[Lab 03: Splunk SIEM Detection](https://github.com/carvalhonishant/lab-03-splunk-siem)**
SSH brute force detection in Splunk: SPL correlation search, a scheduled alert, and a dashboard.

**[Lab 04: Python SSH Log Parser](https://github.com/carvalhonishant/lab-04-python-log-parser)**
A Python tool that parses SSH logs and flags brute force, breaches and known bad IPs, with JSON output and automation friendly exit codes.

**[Lab 05: AWS IAM Misconfiguration](https://github.com/carvalhonishant/lab-05-aws-iam-misconfig)**
Built deliberate IAM misconfigurations in AWS, caught them with Prowler, remediated with the CLI, and verified with a before and after scan.

**[Lab 06: Detecting IAM Attacks in CloudTrail](https://github.com/carvalhonishant/lab-06-aws-cloudtrail-detection)**
Reconstructed an IAM attack from AWS CloudTrail and built a Python and boto3 tool that flags risky IAM activity by severity.
