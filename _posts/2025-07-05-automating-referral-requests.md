---
layout: post
title: "Automate Referral Requests with Python"
cover_image: /assets/automate_referral_requests.jpg
tags: python, cli, automation, jobsearch
date: 2025-07-05
---


As a job seeker, one of the most effective strategies is to reach out to current employees at your target companies and ask for a referral. But doing this manually — finding people, writing messages, tweaking each one — can be time-consuming and exhausting.

So I thought, **why not automate it?**

Introducing **Referral Email CLI Tool** — a simple command-line tool that personalizes and sends referral request emails to a list of employees, using a single template and your Gmail account.

---

## 💡 The Idea

I wanted to build something that could:
- Read a list of employee emails from a CSV
- Use a common email template
- Insert personalized details like company name, role, and pitch
- Preview the emails before sending
- Send them securely via Gmail
- Log everything for future tracking

---

## ⚙️ Tech Stack

- **Python 3**
- [Jinja2](https://palletsprojects.com/p/jinja/) for templating
- [python-dotenv](https://pypi.org/project/python-dotenv/) for config
- **SMTP** (via `smtplib`) to send emails
- CSV file for employee contacts

---

## 🚀 What It Does

- Reads employee data (name + email) from a CSV
- Personalizes a referral request using a template
- Sends emails via Gmail (App Password)
- Logs all activity in a CSV

---

## 🔐 Secure Setup
- Use Gmail App Passwords (not your main password)
- Keep `.env`, logs, and contacts out of GitHub

---

## 📎 Try It Out
GitHub: [[github.com/yourusername/referral-cli](https://github.com/mr-prantik/referralCLI_tool)]

Like the project? Star it ⭐ or fork it! Contributions welcome.

---

Thanks for reading & best of luck with your applications! 🙌

