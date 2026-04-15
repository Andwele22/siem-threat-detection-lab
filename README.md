
# siem-threat-detection-lab

## Overview
This project demonstrates my ability to monitor and analyze network traffic using SIEM tools to detect suspicious activity and potential security threats. The lab simulates a real-world Security Operations Center (SOC) environment.

## Tools Used
- Splunk
- Security Onion
- Linux
- Windows

## Objectives
- Monitor logs for suspicious activity
- Detect potential security threats
- Create alerts for real-time monitoring
- Analyze and document findings

## Key Activities
- Ingested and analyzed log data using Splunk
- Monitored authentication logs for failed login attempts
- Identified unusual IP activity and traffic patterns
- Created alerts to detect suspicious behavior
- Investigated potential indicators of compromise (IOCs)

## Sample Findings
- Multiple failed login attempts from a single IP address (possible brute force attack)
- Unusual login times outside normal user behavior
- Suspicious IP addresses attempting access

## Outcome
This project strengthened my ability to work with SIEM tools, analyze logs, and detect threats in a simulated SOC environment.
## Screenshots & Analysis

### 🔍 Log Analysis Example
The following logs were analyzed in Splunk to identify suspicious activity:

- Multiple failed login attempts detected from IP: 192.168.1.10  
- Login attempts occurred within a short time frame  
- Activity pattern indicates possible brute-force attack  

### 🚨 Alert Configuration
Created a custom alert in Splunk to detect:
- More than 5 failed login attempts within 2 minutes  
- Triggered alert for suspicious IP activity  

### 📊 Dashboard Monitoring
Monitored:
- Authentication logs  
- Login success vs failure rates  
- Source IP behavior patterns  

### 🧠 Key Insight
Identified abnormal login behavior outside normal usage patterns, demonstrating the importance of continuous monitoring and alerting in a SOC environment.

