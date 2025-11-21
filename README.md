# DevOps-Intern-Assignment
DevOps EC2 + Monitoring + CloudWatch Assignment

# DevOps Intern Assignment – Hari Aravind S

This repository contains the solutions for the DevOps Intern Assignment including automation scripting, web server setup, scheduled monitoring, and AWS CloudWatch integration.

---

## 🔹 Task A: EC2 Configuration

✔ Launched Ubuntu EC2 instance  
✔ Allowed SSH & HTTP traffic via Security Group  
✔ Connected via SSH to instance  
✔ Installed & configured NGINX web server  
✔ Hosted a custom webpage showing:
- Hello, I am HARI ARAVIND S  
- Instance ID (via metadata)  
- Uptime (via system command)

---

## 🔹 Task B: System Monitoring & CloudWatch

✔ Created a monitoring script:  
`/usr/local/bin/system_report.sh`  
Captures:
- Time & uptime
- CPU, memory & disk usage
- Top 3 CPU consuming processes

✔ Output logged to `/var/log/system_report.log`

✔ Cron job scheduled to run every 5 minutes:


✔ Installed AWS CLI  
✔ Configured IAM programmatic user and keys  
✔ Created Log Group: `/devops/intern-metrics`  
✔ Created Log Stream: `system-report-stream`  
✔ Uploaded logs to CloudWatch using AWS CLI

---

## 📁 Repository Structure


---

## 🧑‍💻 Tools & Technologies Used

- AWS EC2 (Ubuntu)
- NGINX Web Server
- Bash Scripting
- Cron Scheduler
- AWS CLI & CloudWatch
- Linux Administration

---

## 🏁 Final Status

🎯 All tasks completed successfully  
📌 Logs successfully visible in AWS CloudWatch  
📌 Documentation uploaded in repo

---

### 🔗 Author

**Hari Aravind S**

