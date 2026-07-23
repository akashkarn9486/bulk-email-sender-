
# 📧 Bulk Personalized Email Dashboard

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://python.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.28%2B-FF4B4B?logo=streamlit)](https://streamlit.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fyourusername%2Fbulk-email-dashboard&label=Visitors&countColor=%23263759)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fyourusername%2Fbulk-email-dashboard)

Send personalized bulk emails, track delivery status in real‑time, and export a professional PDF report – all from a single Streamlit dashboard.

---

## 📑 Table of Contents

- [Features](#-features)
- [Demo](#-demo)
- [Installation](#-installation)
- [Usage](#-usage)
  - [1. Launch the App](#1-launch-the-app)
  - [2. Configure SMTP (Sidebar)](#2-configure-smtp-sidebar)
  - [3. Compose Your Email](#3-compose-your-email)
  - [4. Add Recipients](#4-add-recipients)
  - [5. Attach a File (Optional)](#5-attach-a-file-optional)
  - [6. Send Emails](#6-send-emails)
  - [7. View Status & Export Report](#7-view-status--export-report)
- [SMTP Provider Settings](#-smtp-provider-settings)
- [App Passwords (Gmail, Outlook, etc.)](#-app-passwords-gmail-outlook-etc)
- [CSV Format for Recipients](#-csv-format-for-recipients)
- [Email Status Tracking](#-email-status-tracking)
- [PDF Report](#-pdf-report)
- [Troubleshooting](#-troubleshooting)
- [Customization](#-customization)
- [License](#-license)
- [Acknowledgements](#-acknowledgements)

---

## ✨ Features

- **SMTP integration** – Works with Gmail, Outlook, Yahoo, Office 365, or any custom SMTP server.
- **Personalization** – Use `{name}` placeholder in subject and body; each recipient receives a unique message.
- **Two recipient input methods**:
  - Manual table editor directly in the app.
  - Upload a CSV with `name` and `email` columns.
- **File attachment** – Attach one file (PDF, image, etc.) that goes to all recipients.
- **Real‑time progress** – Watch a progress bar and live counter while emails are sent.
- **Delivery tracking** – Every send attempt logged as **Sent** or **Failed**, with error details.
- **PDF export** – Download a formal campaign report with summary, per‑recipient status, and timestamps.
- **Secure credentials** – All credentials are entered in the sidebar and never stored; they live only for the session.

---

## 🎬 Demo

*Insert a GIF or screenshot of the dashboard here.*

> **Dashboard main view**  
> ![Dashboard compose tab](images/compose.png)  
> *Compose email, add recipients, and send.*

> **Status & Report tab**  
> ![Status and PDF export](images/status.png)  
> *Review delivery status and download the PDF report.*

---

## 🚀 Installation

### Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/bulk-email-dashboard.git
cd bulk-email-dashboard
