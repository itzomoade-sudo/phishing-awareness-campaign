# Phishing Awareness Campaign Lab

## 📌 Project Overview

This project documents a controlled **phishing awareness campaign** conducted in a Kali Linux lab environment using **GoPhish**.

The purpose of the exercise was to understand how phishing simulations work, identify common indicators of phishing attacks, and demonstrate how security teams can measure user awareness through controlled security testing.

> ⚠️ **Disclaimer:** This project was conducted strictly in a controlled lab environment for cybersecurity education and awareness. No unauthorized users, systems, or accounts were targeted, and no real credentials were collected.

---

## 🎯 Objectives

The main objectives of this project were to:

- Understand the workflow of a phishing awareness simulation.
- Configure and use GoPhish in a controlled environment.
- Create a simulated phishing email template.
- Configure a test sending profile.
- Create and launch a controlled awareness campaign.
- Monitor campaign results.
- Analyze user interaction with the simulated email.
- Understand how phishing awareness can be measured.

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Kali Linux | Security testing environment |
| GoPhish | Phishing simulation and awareness platform |
| Gmail | Test email account |
| Firefox | Accessing the GoPhish web interface |

---

## 🧪 Lab Environment

The campaign was performed locally within a controlled cybersecurity lab.

**Platform:** Kali Linux  
**Simulation Tool:** GoPhish  
**Environment:** Controlled/Lab Environment  
**Purpose:** Security Awareness & Phishing Simulation

---

# 🔧 Project Workflow

The simulation followed these stages:

```text
Kali Linux
     │
     ▼
 GoPhish Setup
     │
     ▼
Email Template
     │
     ▼
Sending Profile
     │
     ▼
Landing page
     |
Test Campaign
     │
     ▼
Campaign Execution
     │
     ▼
Results & Analysis

1. Email Template Configuration
A simulated email template was created inside GoPhish.
The template was used to demonstrate how a phishing-style message can be structured and presented during an awareness exercise.

<img width="1920" height="909" alt="Screenshot_2026-09-08_19_28_02" src="https://github.com/user-attachments/assets/0b98b30b-3182-467d-a738-5e4e190e9c60" />

2. Test Email
A test email was sent to a controlled test account to verify that the GoPhish configuration was working correctly.
The test confirmed that the email could be delivered successfully.
<img width="1920" height="909" alt="Screenshot_2026-09-08_19_06_30" src="https://github.com/user-attachments/assets/364617d6-0f73-4b64-a333-06af5dd32891" />

3. Sending Profile
A GoPhish sending profile was configured for the controlled campaign.
The sending profile was tested before launching the campaign.
<img width="1920" height="909" alt="Screenshot_2026-09-08_19_06_05" src="https://github.com/user-attachments/assets/7c73d967-c525-429b-8f7d-7d09e7420beb" />

4. Campaign Configuration
A campaign was created using:
The simulated email template
The configured sending profile
A controlled test group
A local/lab landing page
The campaign was then scheduled for execution.

<img width="1920" height="909" alt="Screenshot_2026-09-08_19_43_01" src="https://github.com/user-attachments/assets/70d8810b-e9b4-412a-a779-e71693b24a5e" />

5. Campaign Results
After the campaign was executed, GoPhish provided statistics showing how the test recipient interacted with the simulated message.
Observed Results
Metric
Result
Emails Sent
2
Emails Opened
1
Links Clicked
1
Data Submitted
1
Emails Reported
0
These results demonstrate how phishing simulation platforms can be used to measure user interaction and awareness.

<img width="1920" height="909" alt="Screenshot_2026-09-08_19_57_01" src="https://github.com/user-attachments/assets/566b8f1f-b3f4-4cd1-8d56-ce0602bd1a94" />

📊 Key Findings
The simulation demonstrated several important phishing-awareness concepts:
1. Email delivery is only the first stage
A successful delivery does not necessarily mean an attack will succeed. User interaction is an important factor.
2. Phishing messages can encourage users to act quickly
Security awareness training should teach users to recognize suspicious messages, unexpected offers, urgent requests, and unfamiliar links.
3. User interaction can be measured
GoPhish provides campaign metrics that can help security teams evaluate awareness and identify areas where additional training may be required.
4. Security awareness is an important defensive layer
Technical security controls are important, but users also play a significant role in preventing phishing attacks.
🛡️ Defensive Recommendations
Based on the exercise, users should:
Verify unexpected emails before interacting with them.
Check the sender's address carefully.
Avoid clicking suspicious links.
Be cautious of unexpected prizes, offers, or urgent requests.
Verify requests through an independent communication channel.
Report suspicious emails to the appropriate security team.
Use multi-factor authentication (MFA) where available.
Participate regularly in security-awareness training.
📚 What I Learned
Through this project, I gained practical experience with:
GoPhish
Phishing awareness simulations
Email security concepts
Campaign configuration
Security awareness testing
Interpreting phishing campaign metrics
Basic analysis of user interaction
Defensive security practices
🔐 Ethical Considerations
This project was performed for educational and defensive cybersecurity purposes.
The simulation was restricted to accounts and systems within a controlled laboratory environment.
No attempt was made to compromise real users, organizations, or systems.
The project demonstrates the importance of conducting phishing simulations responsibly and with proper authorization.
🚀 Skills Demonstrated
Cybersecurity:
Phishing Awareness • Email Security • Security Testing • Social Engineering Awareness
Tools:
Kali Linux • GoPhish • Firefox
Security Concepts:
Security Awareness • Phishing Detection • User Awareness • Defensive Security
👨‍💻 Author
Yusuf Tajudeen 
Cybersecurity Student | SOC & Cloud Security Enthusiast
GitHub: itzomoade-sudo⁠�
⭐ Project Purpose
This project is part of my cybersecurity learning journey and practical lab portfolio, with a focus on developing skills relevant to SOC Analysis, Cloud Security, and Defensive Cybersecurity.
