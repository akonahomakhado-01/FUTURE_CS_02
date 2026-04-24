# FUTURE_CS_02
PHISHING task 2
# Phishing Detection & Awareness System 🛡️

## Project Overview
This project was developed during my **Cybersecurity Internship** to demonstrate a professional approach to identifying, analyzing, and mitigating phishing threats. The core of this project is a forensic audit of a credential harvesting email that successfully bypassed technical filters (**SPF/DKIM: PASS**) by utilizing legitimate infrastructure.

##  Key Features
* **Technical Forensic Audit:** Deep-packet inspection of email headers to identify sender origin and routing paths.
* **Authentication Analysis:** A detailed breakdown of why cryptographic signatures (SPF, DKIM) are necessary but not sufficient for security.
* **Risk Assessment:** Evaluation of the business impact and risk score (Likelihood vs. Impact).
* **Awareness System:** A "Look-Hover-Report" framework designed to strengthen the organizational "Human Firewall."

##  Project Structure
* `Phishing_Analysis_Report.pdf`: The complete, professional security audit.
* `Evidence/`: A folder containing screenshots of the phishing email and Google Admin Toolbox results.
* `Raw_Headers.txt`: The unedited metadata used for the forensic investigation.

##  Tools Used
* **Google Admin Toolbox (Messageheader):** For metadata verification and authentication alignment.
* **NIST Cybersecurity Framework:** Guided the detection and response strategy.
* **Manual Heuristic Analysis:** For identifying social engineering triggers.

##  Investigation Summary
During the investigation, I discovered that the attacker utilized a valid Gmail account (`internationals191@gmail.com`) to send a spoofed "Security Breach" notice. While the email technically originated from a trusted server, the **intent** was fraudulent. The analysis highlights the importance of looking beyond technical "PASS" results and inspecting contextual indicators like suspicious destination domains (`http://edu-portal-auth.com`).

##  About Me
I am **Akonaho Makhado**, a Cybersecurity student at **Eduvos**. I am passionate about threat hunting, network security, and helping organizations build resilient defense strategies.

---
*Disclaimer: This project was conducted for educational and simulation purposes as part of a cybersecurity internship program.*
