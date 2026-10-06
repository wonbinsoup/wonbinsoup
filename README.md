<h1 align="center">Hi, I'm Daniel</h1>
<h3 align="center">Computer Science @ Northeastern University</h3>
<h3 align="center">CS Student Focused on Cloud & Application Security</h3>

## 👋 About Me

CS student building hands-on skills in cloud and application security, with a focus on IAM misconfigurations, privilege escalation, and web application vulnerabilities.

Currently working toward my AWS Cloud Practitioner certification, and active in NUSecurity and NU CCDC. My interest in security started after my high school was hit by a ransomware attack — I wanted to understand how systems like that actually get compromised, which led me to start building and breaking things on my own.

## 🛠️ Core Stack

**Languages**
`Python` `Java` `SQL` `C` `Bash`

**Frameworks & Tools**
`Flask` `SQLite` `Burp Suite` `CyberChef` `Git`

**Cloud & Infra**
`AWS` `boto3` `Linux` `MongoDB` `Redis`

## 💻 Selected Work

### 🔐 IAM Privilege Escalation Scanner
`Python` • `boto3` • `AWS IAM`

A CLI tool that scans AWS IAM users, roles, and groups for privilege escalation paths — permission combinations that let a low-privilege identity gain unauthorized admin access. Implements 10+ real escalation techniques sourced from Rhino Security Labs research, with severity classification and remediation steps for each finding.

Building this taught me that the real risk in IAM usually isn't one bad permission — it's dangerous *combinations*, like pairing `iam:PassRole` with `lambda:CreateFunction`, that let someone chain their way to admin access.

→ [View Project](https://github.com/wonbinsoup/IAM-Privilege-Escalation-Scanner)

### 🧪 Flask SQLi & XSS Lab
`Python` • `Flask` • `SQLite` • `Burp Suite` • `CyberChef`

A deliberately vulnerable Flask/SQLite web app built to demonstrate SQL injection and XSS (OWASP Top 10), then fixed using parameterized queries and Jinja2 auto-escaping. Used Burp Suite to intercept and manipulate HTTP requests and CyberChef to encode payloads, replicating a full exploitation-and-remediation workflow.

→ [View Project](https://github.com/wonbinsoup/flask-sqli-xss-lab)

## 📫 Reach Me

[LinkedIn](https://linkedin.com/in/daniel-w-kim) · kdaniel1324@gmail.com

⚡ Fun fact: Pierce the Veil is my favorite band.
