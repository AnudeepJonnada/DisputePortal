# 🔐 Transaction Dispute Resolution Portal

> A secure, low-code solution built on Microsoft Power Platform to manage transaction disputes, automate notifications, and analyze fraud resolution data. Tailored for Navy Federal Credit Union’s dispute resolution workflow.

---

## 🎯 Project Overview

The **Dispute Resolution Portal** enables users to submit transaction disputes and staff to manage and resolve them — all through a clean dual-view Power App. It leverages Microsoft 365 tools for process automation, analytics, security, and Agile tracking.

| Feature                      | Tool Used                     |
|-----------------------------|-------------------------------|
| Dispute Submission Portal   | Power Apps (Canvas App)       |
| Notifications               | Power Automate (Email Flows)  |
| Data Storage                | SharePoint (DisputeRecords)   |
| Analytics Dashboard         | Power BI (Optional for Mac)   |
| Agile Tracking              | Azure DevOps                  |
| Documentation + Screenshots| GitHub                        |

---

## 🚀 Features

- ✍️ **User Submission Form** with fields:
  - Transaction ID
  - Date
  - Reason
  - Contact Info
  - Attachments (Evidence)
  - Status dropdown (Pending, In Progress, Resolved)

- 👨‍💼 **Admin View**:
  - Gallery of submitted disputes
  - Filtering by Status
  - Inline status updates

- 🔁 **Automation Flows**:
  - 📩 Confirmation Email to user on submission
  - ⏱ Reminder Email to admin if unresolved after 2 days

- 📊 **(Optional) Power BI Dashboard**:
  - Disputes by Card Type
  - Average Resolution Time
  - Total Open Cases

- 🔐 **Azure AD Authentication**:
  - Only logged-in users can submit/view
  - Personalized greeting via `User().FullName`

---

## 📂 Folder Structure

```bash
DisputePortal/
├── README.md
├── AGILE.md
├── /screenshots            # UI + SharePoint + Flow screenshots
├── /flows                  # Power Automate Flow exports (.zip/.json)
├── /docs                   # Azure DevOps board screenshots, slides
