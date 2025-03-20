# 🔍 Security Tools for Information Security  

## 📌 Overview  
As part of an **information security course at the University of Maryland**, I conducted **web penetration testing, forensic analysis, and social engineering attacks** to assess vulnerabilities in a **food-chain company’s application**. The project focused on **detecting security breaches, analyzing attack vectors, and implementing security defenses** using various security tools.  

---

## 🛠 Key Contributions  

- 🏴‍☠️ **Executed social engineering attacks** to acquire **user credentials** and retrieve **flags via web attacks and privilege escalation**.  
- 🔍 **Performed forensic analysis** on a **compromised food-chain company application**, using **Splunk, Snort, Nessus, and Wireshark** to identify attack traces.  
- ⚡ **Conducted web application penetration testing**, exploiting **insecure authentication, SQL injection, and XSS vulnerabilities**.  
- 🛡 **Developed effective security strategies** and provided **mitigation recommendations** to proactively prevent cyber-attacks.  
- 🔄 **Analyzed logs and network traffic** to detect **security breaches and anomalies** in compromised systems.  

---

## 🛠 Tools & Technologies Used  

| Category                     | Tools & Technologies |
|------------------------------|----------------------|
| 🔍 SIEM & Log Analysis       | Splunk |
| 🛡 Network Intrusion Detection | Snort, Wireshark |
| 🚀 Vulnerability Scanning    | Nessus |
| 🏴‍☠️ Web Penetration Testing | Burp Suite, SQLMap |
| 🔑 Privilege Escalation      | Linux Privilege Escalation Scripts |
| 🎭 Social Engineering        | Phishing Simulations, Credential Harvesting |
| 📜 Security Recommendations  | Threat Intelligence, Cyber Defense Strategies |

---

## ⚙️ Sample Attack & Analysis Commands  

### 🏴‍☠️ Exploiting SQL Injection with SQLMap  
```bash
sqlmap -u "http://target.com/login.php?id=1" --dbs --dump
```
🔍 Detecting Network Attacks Using Snort
```bash
snort -A console -q -c /etc/snort/snort.conf -i eth0
```
📜 Analyzing Compromised Logs in Splunk
```splunk
index=web_logs "failed login attempt" | stats count by user
```
🛡 Capturing Suspicious Network Traffic with Wireshark
```bash
tshark -i eth0 -w capture.pcap
```


⸻

📋 Final Report & Evaluation

The project concluded with a comprehensive security analysis report, detailing:

✅ Findings from web penetration testing, including exploited authentication and privilege escalation vulnerabilities.
✅ Forensic analysis results, identifying attack patterns, logs, and security gaps in the compromised application.
✅ Threat intelligence insights, providing proactive security strategies for risk mitigation.
✅ Mitigation plan recommendations, covering SIEM monitoring, intrusion detection, and endpoint hardening.
✅ Final presentation & documentation, demonstrating how security tools enhance cyber defense capabilities.

⸻

🎤 Presentation & Impact

I compiled the findings, attack scenarios, and security solutions into a technical security report, outlining real-world cyber threat mitigation techniques.

⸻

💬 Have Questions?

Feel free to reach out or open an issue! 🚀🔐
