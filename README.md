# -Phishing-Email-Analysis-Project
## 🎯 Project Objective

The goal of this project is to demonstrate practical **email security analysis skills** by identifying, analyzing, and responding to potentially malicious emails using SOC methodologies and tools.

This project simulates a real-world **Security Operations Center (SOC)** workflow and is designed for **portfolio and job applications**.

## 🧠 Skills Demonstrated

- Email header analysis
- Phishing & malware detection
- SPF, DKIM, DMARC interpretation
- IOC extraction
- Threat classification
- Incident response decision-making
- Documentation & reporting

## 🛠 Tools & Technologies Used

- Thunderbird (Email client)
- Kali Linux 
- Online header analyzers
- VirusTotal
- phishtool
- urlscan.io
- WHOIS lookup tools
- MITRE ATT&CK framework

## 📨 Step 1: Email Overview

- **Sender Address:** info@libreriacies.es
- **Recipient:** jdgelok@gmail.com
- **Subject:** Binance Cybersecurity
- **Date Received:**  Tue, 25 Jul 2023 12:47:32

## Initial suspicion based on email body:

![](https://github.com/Temijr2014/-Phishing-Email-Analysis-Project/blob/main/emailbody%20binance.png?raw=true)

- “Get compensated in Bitcoin”
Legitimate companies (including Binance) don’t proactively offer compensation in BTC via unsolicited emails.

- Vague, alarming language
“Leaks of personal data”
“More than 120 leaks”
No specifics, no dates, no affected services, no evidence.

- Fake-sounding authority
“Official Service for Control and Compensation Payments”
“Cybersecurity department for the control of personal data”
These are not real, standard Binance department names.

- Generic personalization
“Personal notification No. 6508445”
No name, no account ID, no verifiable reference inside your Binance account.

- Pressure + incentive combo
Fear (“your data was leaked”) + reward (“get compensated”) is a classic scam tactic.

- Email-based action
Binance normally asks you to log in via their official app or website, not click compensation links from emails.

## 🧾 Step 2: Header Analysis

Analyzed the full email headers to determine:

- Sending mail server IP
- SPF result
- DKIM signature
- DMARC policy

## Findings

![](https://github.com/Temijr2014/-Phishing-Email-Analysis-Project/blob/main/Screenshot_2026-01-11_18_50_10.png?raw=true)

![](https://github.com/Temijr2014/-Phishing-Email-Analysis-Project/blob/main/Screenshot_2026-01-11_19_10_52.png?raw=true)

## 🔗 Step 3: URL & Attachment Analysis

### URLs

- Extracted embedded links
![](https://github.com/Temijr2014/-Phishing-Email-Analysis-Project/blob/main/Screenshot_2026-01-11_18_47_53.png?raw=true)
- Checked reputation on VirusTotal
![](https://github.com/Temijr2014/-Phishing-Email-Analysis-Project/blob/main/Screenshot_2026-01-11_18_49_32.png?raw=true)
