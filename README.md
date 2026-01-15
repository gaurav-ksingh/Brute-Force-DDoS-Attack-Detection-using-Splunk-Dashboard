# Brute Force & DDoS Attack Detection using Splunk Dashboards
# Project Description

This project demonstrates detection and visualization of Brute Force and DoS/DDoS attacks using Splunk dashboards and correlation logic. The goal is to simulate real SOC alerting and monitoring workflows.

# Tools & Technologies

Splunk Enterprise
SPL (Search Processing Language)
Simulated attack log dataset
SIEM detection logic


# Detection Scenarios Implemented
## Brute Force Attack Detection

Multiple failed login attempts from the same source IP
Time-based correlation using buckets
Threshold-based detection logic
Identification of attacker IPs and targeted accounts

## DoS / DDoS Attack Detection

Sudden spike in HTTP request volume
Traffic anomaly detection using timecharts
Source IP-based traffic analysis
High-frequency request detection

# SPL Correlation Logic

Time-window based aggregation
Threshold filtering using where clause
Multi-event correlation using stats
Realistic SOC detection logic

# Dashboard
<img width="860" height="1350" alt="image" src="https://github.com/user-attachments/assets/6fea5c43-3129-47e3-88ec-3945ab5d21f2" />


# Brute force attack trend visualization
Top attacking IP addresses
Login failure spikes over time
DDoS traffic spike visualization
Requests per second analysis

# Outcome

Designed SOC-style dashboards for attack visibility
Implemented correlation-based detection logic
Gained hands-on experience with SIEM alerting concepts
Understood difference between alerts and dashboards

# HOW TO USE
1. Upload dataset into Splunk
2. Verify index and time range
3. Run SPL queries provided
4. Create dashboards using panel searches
5. Convert detection queries into alerts if required

# KEY SKILLS DEMONSTRATED 

SIEM Log Analysis (Splunk)
SOC Monitoring & Detection
SPL Query Writing
Brute Force Detection
DoS/DDoS Traffic Analysis
Security Dashboards
Correlation Logic
Incident Detection Fundamentals







