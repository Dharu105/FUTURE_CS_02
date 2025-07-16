# 🔐 Internship Task – Security Alert Monitoring

## 📘 About the Project

This internship task focuses on analyzing security alerts and suspicious logs using tools like Elastic Stack (Elasticsearch, Logstash, Kibana) and Splunk. The goal was to detect unusual behavior in system logs and write a report based on the findings.

---

## 🛠️ Tools Used

- Elasticsearch and Kibana (ELK Stack)
- Splunk Trial
- Burp Suite (for simulated requests)
- jwt.io (for token analysis)

---

## 📄 What’s Included

- 📝 Task Report – contains log analysis, visualizations, and conclusions  
- 📂 Queries – filters written in KQL used to detect access attempts  
- 📁 Notes – summary of findings and explanations

---

## ✅ Key Findings

- Repeated failed access to `/admin` endpoint detected  
- IP `192.168.0.1` showed signs of probing and privilege escalation attempts  
- Payload sizes were mostly stable but revealed system behavior clues  
- Suggested actions include stronger access controls and alert rules

---

🔎 This task was done as part of my internship to learn more about SOC workflows and threat detection.
