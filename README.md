# What is the use of SIEM Alert Simulator?
SIEM Alert Simulator provides pre-generated sample logs mimicking real-world security incidents like failed logins, port scans, and malware alerts. These logs help users practice ingestion, detection, and alert triaging in SIEM platforms such as Splunk.
# Prerequisites
* SIEM platform installed (Splunk, Graylog, ELK Stack) or access to one
* Basic knowledge of SIEM log ingestion and alerting
# Usage
* Download or clone the repository to your local machine.
* Upload sample log files located in the sample_logs/ folder into your SIEM platform.
* Create detection rules and alerts based on suspicious activities like brute-force attempts or port scans.
# Folder Structure
* sample_logs/ — contains sample fake security logs
* README.md — project documentation
# How to Ingest Logs
* Splunk: Settings → Add Data → Upload files from sample_logs/
* Graylog: Configure File Input to ingest logs from sample_logs/
* ELK: Use Logstash file input or Beats to ingest log files
# Benefits
*Practice alert triaging and incident response workflows
* Simulate SOC analyst tasks in a controlled environment
* Gain hands-on experience with SIEM log ingestion and alert creation
* Build practical skills in detecting suspicious activities like brute-force attacks
* Enhance your readiness for SOC roles and security analyst interviews                   
