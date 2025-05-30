# Automailor-with-merging
# 📧 Gmail Mail Merge Automator

A simple Python script that automates personalized email sending using the Gmail API. Ideal for sending bulk invitations, announcements, or any kind of mail merge.

---

## ✨ Features

- Authenticates via Gmail API with OAuth 2.0
- Sends customized emails to multiple recipients
- Personalizes each message with recipient names
- Uses plain text files for names and email content

---

## 🔧 Requirements

- Python 3.6+
- Gmail account
- `credentials.json` from Google Cloud Console
- The following Python packages:
  - `google-auth-oauthlib`
  - `google-api-python-client`

Install the required packages:

```bash
pip install google-auth-oauthlib google-api-python-client
