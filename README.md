# Phishing Email Identifier

## 1. Project Title
**Phishing Email Identifier using Python**

## 2. Objective
To develop a basic Python-based phishing email identifier that analyses email information and detects common suspicious indicators such as unknown senders, urgent messages, suspicious links, requests for sensitive information, and potentially dangerous attachments.

## 3. Basic Features
- Accepts sender email address.
- Analyses email subject and message.
- Detects suspicious sender names.
- Identifies urgent or threatening language.
- Detects requests for sensitive information.
- Checks suspicious links.
- Identifies potentially dangerous attachments.
- Calculates a risk score.
- Classifies emails as:
  - No Obvious Red Flags
  - Suspicious Email
  - Likely Phishing

## 4. Technologies Used
- Programming Language: Python 3
- Operating System: Kali Linux / Ubuntu
- Concepts: String Operations, Conditional Statements, Loops, Lists, Score-Based Detection.

## 5. Installation and Execution

Install Python 3:

```bash
sudo apt update
sudo apt install python3 -y
```

Clone the repository:

```bash
git clone https://github.com/USERNAME/Phishing-Email-Identifier.git
cd Phishing-Email-Identifier
```

Run the program:

```bash
python3 phishing_identifier.py
```

## 6. Sample Output

```text
=======================================================
          LIVE PHISHING EMAIL IDENTIFIER
=======================================================

Enter sender email: security@unknown-alert.example
Enter email subject: URGENT Account Suspended
Enter email message: Verify your password immediately
Enter email link: http://fake-login.example
Enter attachment name (if any):

=======================================================
              ANALYSIS REPORT
=======================================================

[!] Suspicious sender name
[!] Urgent or threatening language detected
[!] Request for sensitive information
[!] Link does not use HTTPS
[!] Link contains suspicious keywords

Risk Score: 7

RESULT: LIKELY PHISHING

=======================================================
```

## 7. Learning Outcomes
- Understanding phishing attacks and social engineering.
- Identifying common phishing email indicators.
- Learning basic email security analysis.
- Understanding suspicious URLs and attachments.
- Applying Python string operations for threat detection.
- Developing a basic rule-based cybersecurity tool.

## 8. Project Demonstration

### Live Demo Video

[![Watch Phishing Email Identifier Demo](https://drive.google.com/thumbnail?id=1NFm8LN6Csrup9Dzq2wh9fS8NYl64DP9H&sz=w1000)](https://drive.google.com/file/d/1NFm8LN6Csrup9Dzq2wh9fS8NYl64DP9H/preview)

**[▶ Watch Phishing Email Identifier Demonstration](https://drive.google.com/file/d/1NFm8LN6Csrup9Dzq2wh9fS8NYl64DP9H/view)**

## Author
Cybersecurity Internship Demonstration Project.

**Note:** This is a basic educational rule-based detector. It does not guarantee that an email is safe or malicious. HTTPS links can also be used in phishing attacks.
