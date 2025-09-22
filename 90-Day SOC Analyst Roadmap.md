# 🛡️ 90-Day SOC Analyst Roadmap  

## Phase 1: Foundations (Week 1–3)  
**Goal:** Build core cybersecurity knowledge and environment.  

### Week 1  
- Learn networking fundamentals (OSI, TCP/IP, ports, DNS, HTTP/HTTPS).  
- Study Linux & Windows basics (commands, file system, event logs).  
- Setup a lab: VMware/VirtualBox with Ubuntu + Windows VM.  

### Week 2  
- Cybersecurity basics: CIA triad, threats, vulnerabilities, attacks.  
- Learn log analysis basics (syslog, Windows Event Viewer).  
- Explore MITRE ATT&CK framework (Initial Access, Execution, Persistence).  

### Week 3  
- Study incident response lifecycle (Preparation → Detection → Containment → Eradication → Recovery).  
- Familiarize with security tools (Wireshark, Nmap, Sysinternals).  
- **Project:** Capture & analyze network traffic with Wireshark.  

---

## Phase 2: SIEM & Detection (Week 4–6)  
**Goal:** Hands-on with SOC tools.  

### Week 4  
- Learn SIEM concepts (log ingestion, parsing, correlation).  
- Install & configure **Wazuh SIEM** or Splunk Free.  
- Forward logs from Ubuntu & Windows to SIEM.  

### Week 5  
- Write detection rules/queries:  
  - Failed login attempts (brute force).  
  - Port scan detection.  
  - Suspicious PowerShell command.  
- Learn alert triage (false positives vs true positives).  

### Week 6  
- **Project:** Build SOC dashboard (Top IPs, Failed logins, Malware alerts).  
- Practice threat hunting with Splunk SPL / Wazuh rules.  
- Study Suricata IDS basics (signature vs anomaly detection).  

---

## Phase 3: Incident Response & Threat Hunting (Week 7–9)  
**Goal:** Learn to analyze, respond, and hunt.  

### Week 7  
- Study malware analysis basics (hashing, VirusTotal, YARA).  
- Use **Velociraptor/EDR** for endpoint log collection.  
- **Project:** Detect and investigate simulated malware with Wazuh + VirusTotal integration.  

### Week 8  
- Learn threat hunting methodology (hypothesis → hunt queries → validate).  
- Hunt for lateral movement & privilege escalation in logs.  
- Document findings in a SOC analyst report.  

### Week 9  
- Blue-team simulations:  
  - Brute force attack on SSH.  
  - Suspicious user creation.  
  - DNS tunneling attempt.  
- Map detections to MITRE ATT&CK.  

---

## Phase 4: Career Prep (Week 10–12)  
**Goal:** Portfolio + job readiness.  

### Week 10  
- Resume building: Add SOC projects (SIEM setup, detections, reports).  
- Share GitHub/LinkedIn posts about your lab projects.  

### Week 11  
- Mock interview prep:  
  - Walk through incident response process.  
  - Explain SIEM use cases.  
  - Solve log analysis scenarios.  

### Week 12  
- Take practice tests (CompTIA CySA+ or SC-200).  
- Apply to SOC roles (L1 Analyst, Security Operations Trainee).  
- Keep lab running for continuous practice.  

---

## ✅ By Day 90 You Will Have
- Strong foundation in networking, OS, and security concepts.  
- Hands-on SOC lab with **Wazuh/Splunk, Suricata, Velociraptor**.  
- Detection rules for brute force, port scan, malware, and insider activity.  
- A GitHub/LinkedIn portfolio of your SOC projects.  
- Resume ready for **SOC Analyst L1** interviews.  
