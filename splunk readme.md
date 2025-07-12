# 📊 Splunk Windows Security Monitoring Project

This project demonstrates how to use **Splunk Enterprise** to monitor Windows Security Event Logs and detect suspicious login activities.  
It includes a custom dashboard and an alerting system that sends email notifications for failed login attempts.

---

## 📌 Features

✅ Dashboard with:
- Failed Login Attempts
- Successful Login Attempts
- Account Lockouts

✅ SPL queries for each panel  
✅ Scheduled alert with automatic email notification using Gmail SMTP

---

## ⚙️ Tools Used

- Splunk Enterprise (Free Trial)
- Windows Security Event Logs
- Gmail SMTP (App Password) for email alerts

---

## 🗂️ Files Included

- `Splunk_Windows_Security_Monitoring.pdf` — Full project report with screenshots and explanation
- `screenshots/` — Raw screenshots of dashboard panels and alerts (optional)

---

## 🚀 How It Works

1. Windows Event Logs are collected and indexed by Splunk.
2. SPL queries filter specific Event Codes:
   - `4625` — Failed Login Attempts
   - `4624` — Successful Logins
   - `4740` — Account Lockouts
3. Panels visualize login activity in bar charts.
4. Scheduled alert searches for failed logins and triggers an email if conditions are met.

---

## ✅ Author

**Lokeshwar V**

---

## 📌 Note

This is a beginner-friendly project for practice and learning Splunk basics.  
Future improvements: advanced correlation, additional event types, integration with other SIEM tools.

---
