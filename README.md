# SOC Automation using Splunk, n8n, AI & AbuseIPDB

## 📌 Overview

This project demonstrates an automated SOC workflow that detects brute-force attacks, enriches alerts with threat intelligence, and notifies SOC analysts automatically.

The automation reduces manual investigation time and improves incident response speed.

---

## 🎯 Objectives

* Detect RDP brute-force attacks
* Automate alert enrichment
* Integrate Threat Intelligence (AbuseIPDB)
* Notify SOC analysts via Slack
* Simulate real SOC workflow

---

## 🛠️ Tools & Technologies

* Splunk SIEM
* n8n Automation
* AbuseIPDB Threat Intelligence
* Slack Notification
* AI/LLM Analysis
* Windows 10 Target
* Windows 11 Attacker

---

## 🏗️ Architecture

---

## ⚙️ Workflow

1. Attacker performs RDP brute-force attack from Windows 11
2. Target Windows 10 generates security logs
3. Splunk detects failed login attempts
4. Splunk triggers alert to n8n webhook
5. n8n processes alert using AI/LLM
6. AbuseIPDB enriches IP reputation
7. Response server prepares alert
8. Slack notifies SOC analysts

---

## 🔍 Attack Scenario

* Attack Type: RDP Brute Force
* Event ID: 4625 (Failed Login)
* Log Source: Windows Security Logs
* Detection Platform: Splunk

---

## 📊 Results

* Automated alert generation
* IP reputation enrichment
* Slack notification sent
* Reduced investigation time

---

## 📸 Screenshots
<img src="https://raw.githubusercontent.com/Prashant42125/SOC-AUTOMATION-WITH-N8N/main/Soc_automation_with_n8n.png" width="900">---

## 📚 Skills Demonstrated

* SIEM Alerting
* SOAR Automation
* Threat Intelligence Integration
* Incident Response
* SOC Workflow Automation

---

## 👤 Author

Prashant
CEHv13 | SOC Analyst | Blue Team
