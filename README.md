# phising-email_report-task-2
# 📧 Phishing Email Analysis Report

## 🎯 Objective
The purpose of this task is to analyze a suspicious email and identify key characteristics of phishing. This contributes to cybersecurity awareness by understanding how email spoofing and social engineering tactics are used.

---

## 🧪 Sample Email Details

From: Amazon Billing Center no-reply@amazon.com
Reply-To: billing-support@amazn-checkup.com
To: yourname@example.com
Subject: [ACTION REQUIRED] Your Amazon Payment Could Not Be Processed
Date: Mon, 27 May 2025 06:42:17 +0000
Message-ID: Amazon-ID:1092834-BillingNotice@amazon.com
Received: from mail1.amazn-checkup.com (185.199.109.153)
SPF: PASS
DKIM: FAIL
DMARC: FAIL

---

## 🔍 Phishing Indicators Identified

| #  | Indicator Description                                                                 | Status |
|----|----------------------------------------------------------------------------------------|--------|
| ✅ | **Spoofed Display Name**: “Amazon Billing Center” appears legit but is spoofed        | Yes    |
| ✅ | **Fake Reply-To Address**: Redirects to a typosquatted domain (`amazn-checkup.com`)    | Yes    |
| ✅ | **Received from Suspicious Server**: `mail1.amazn-checkup.com` not related to Amazon   | Yes    |
| ✅ | **DMARC Failure**: Domain spoofing not authorized                                      | Yes    |
| ✅ | **Urgency Tactic**: Uses threatening/urgent language in subject                        | Yes    |
| ✅ | **Typo Domain Trick**: Misspelled "amazon" as "amazn" to deceive                       | Yes    |
| ✅ | **DKIM Failure**: Message not signed by legitimate domain                              | Yes    |

---

## 🧾 Summary

This email is a **confirmed phishing attempt** based on:
- Header analysis (SPF, DKIM, DMARC checks)
- Typosquatting
- Urgent call to action
- Mismatched reply address

---

## ✅ Recommendations

- Never click on suspicious links or download unknown attachments.
- Always verify sender details and domains.
- Report phishing emails to your security team or email provider.
- Use a trusted header analyzer for deeper inspection.

---

## 📂 Tools Used

- 📧 Email Client (sample view)  
- 🛠️ [MXToolbox Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)

---

## 📌 Status

✔️ Completed – Submitted as part of cybersecurity awareness task  
📁 Repository contains screenshot + this analysis in `README.md`.

---

## 📎 Author

**Name:** _[Your Name]_  
**Email:** _[your.email@example.com]_  
**Course:** BSc IT (Cyber Security Specialization)  
**Date:** May 27, 2025  

---

