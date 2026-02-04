# Log-Monitoring-Analysis
Incident detection skills

# Task 12: Log Monitoring & Analysis

## Objective
The objective of this task is to monitor and analyze system logs to identify suspicious activities, detect anomalies, and understand basic SIEM concepts. This task focuses on SSH log analysis using Kali Linux.

---

## Tools Used
- Kali Linux
- systemd journal logs (`journalctl`)
- SSH service logs

---

## Log Sources Analyzed
- SSH service logs using:
  ```bash
  journalctl -u ssh
