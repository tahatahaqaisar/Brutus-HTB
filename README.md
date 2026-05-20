# Brutus-HTB
This repository contains my investigation and analysis of the Brutus Sherlock challenge from Hack The Box  .  The challenge focuses on detecting and analyzing a brute-force attack through log analysis and incident investigation techniques commonly used in Blue Team and DFIR environments.
# Skills Practiced
Log Analysis
Incident Response
Threat Hunting
IOC Identification
Authentication Event Analysis
Blue Team Investigation

# Scenario
The Sherlock simulates a brute-force attack against a target system.
The objective was to investigate the logs, identify attacker activity, determine the attack timeline, and uncover indicators of compromise.

# Investigation Process
Reviewed authentication and system logs
Identified repeated failed login attempts
Correlated timestamps with successful authentication events
Tracked attacker behavior and suspicious activity
Extracted key indicators of compromise (IOCs)

# Key Findings
Source IP responsible for brute-force attempts
Multiple failed login attempts before successful access
Evidence of unauthorized authentication activity
Indicators useful for detection and monitoring

# Lessons Learned
Importance of centralized logging
Detecting brute-force patterns efficiently
Value of event correlation during investigations
Importance of attention to detail in DFIR workflows

# Tools Used
auth.log provided by the Hack The Box Academy
Splunk
Manual Log Correlation

