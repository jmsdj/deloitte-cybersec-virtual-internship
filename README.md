# Cyber Virtual Internship – Deloitte Australia (Cybersecurity Job Simulation)

A **risk-free job simulation experience** designed by Deloitte Australia to help aspiring cybersecurity professionals practice real-world skills.  
This repository documents my journey, tasks, and solutions completed during the **Deloitte Cyber Virtual Internship**.

---

## 📌 Program Description
Does cyber technology intrigue you? This virtual internship provided a chance to explore what it’s like working as a **Cybersecurity Expert** at Deloitte.  

Through simulated client cases, I practiced:
- Identifying security issues leading to leaks of private company data  
- Supporting a client during a cyber security breach  
- Reading and analyzing web activity logs  
- Determining the source of a data breach  
- Identifying suspicious user activity from logs and requests  

This program offered a **hands-on experience** with cybersecurity investigations while reinforcing problem-solving and analytical thinking.

---

## Role & Scenario

**Role:** Cybersecurity Expert  
**Client:** Daikibo Industrials  
**Issue:**  
- A major news outlet leaked sensitive private information about Daikibo.  
- Their assembly line failed, halting production and disrupting supply chains.  
- Daikibo suspects the compromise of Deloitte’s dashboard built for their partner company, Macora.  

My role was to investigate **how the breach happened** and provide **technical insights** to support the client.

---

## Tasks Completed

1. **Determine Attack Vector**  
   - Investigated whether the breach could have originated directly from the internet without VPN access.  

2. **Log File Analysis** (`web_requests.log`)  
   - Examined activity around the suspected attack period.  
   - Key findings:  
     - **IP Address:** `192.168.0.101`  
     - **Timestamp:** `2021-06-26T00:00:48.000Z`  
     - **Request Type:** `GET`  
     - **User ID:** `mdB7yD2dp1BFZPontHBQ1Z`  

3. **Identify Compromised Machines**  
   - Affected endpoints included:  
     - Meiyo Machine  
     - Seiko Machine  
     - Shenzen Machine  
     - Berlin Machine  

4. **Support Client Communication**  
   - Drafted responses and recommendations for stakeholders to address the breach.  

---

## Skills Practiced
- Cybersecurity incident analysis  
- Web log inspection and interpretation  
- Threat detection & response  
- Client communication in high-pressure scenarios  
- Critical thinking & problem-solving  

---

## About Deloitte Australia
Deloitte is one of the world’s leading professional services firms, tackling some of Australia’s biggest challenges.  
This program emphasized Deloitte’s belief in helping individuals **shape their own career paths** while contributing to **building a secure digital future**.

---

## Repository Contents
- `README.md` → Program overview (this file)

### Inside Deloitte-Virtual
- `analysis/` → Findings and notes from log inspections  
- `reports/` → Client support drafts and breach analysis write-ups

---

## Acknowledgments
This simulation was created by **Deloitte Australia** via [Forage Virtual Internships](https://www.theforage.com/).  
Special thanks to Deloitte for designing this engaging program that allowed me to build confidence and practical skills in cybersecurity.  

