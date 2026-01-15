# Brute-Force-DDoS-Attack-Detection-using-Splunk-Dashboard
This project demonstrates detection and visualization of Brute Force and DoS/DDoS attacks using Splunk Dashboard and correlation logic. The goal is to simulate real SOC alerting and monitoring workflows.

# Tools & Technologies
• Splunk Enterprise • SPL (Search Processing Language) • Simulated attack log dataset • SIEM detection logic • Dashboard panels


# Fields in the Dataset

| Field        | Description                         |
|-------------|-------------------------------------|
| timestamp   | Event time                          |
| log_type    | Log source type (http)              |
| src_ip      | Attacker / normal user IP address   |
| dest_ip     | Target server IP                    |
| method      | HTTP method (GET / POST)            |
| uri         | Endpoint accessed or attacked       |
| status      | HTTP response code (200, 302, 401)  |
| user_agent | Browser / curl / automated script  |
| bytes       | Payload size in bytes               |
| attack_type| normal / brute_force / ddos         |


# How to Ingest into Splunk
Settings → Add Data
Upload splunk_bruteforce_ddos_dataset.csv
Source type: csv
Index name: attack_logs
Finish

# Detection Scenarios Implemented
Brute Force Attack Detection
• Multiple failed login attempts from the same source IP • Time-based correlation using buckets • Threshold-based detection logic • Identification of attacker IPs and targeted accounts

# DoS / DDoS Attack Detection
• Sudden spike in HTTP request volume • Traffic anomaly detection using timecharts • Source IP-based traffic analysis • High-frequency request detection 🔹 SPL Correlation Logic • Time-window based aggregation • Threshold filtering using where clause • Multi-event correlation using stats • Realistic SOC detection logic

# Outcome
• Designed SOC-style dashboards for attack visibility • Implemented correlation-based detection logic • Gained hands-on experience with SIEM alerting concepts • Understood difference between alerts and dashboards
