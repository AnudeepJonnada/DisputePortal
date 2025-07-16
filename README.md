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

    ## 🎥 Demo Video
## 🎥 Demo Video

Watch the user experience in action:

[![Watch the demo] (https://www.loom.com/share/cb906b21baf84c6e8478f0ac2118a241?sid=4531c674-4e1f-4bf2-8a59-a3fd1524c9a1)]



- 👨‍💼 **Admin View**:
  - Gallery of submitted disputes
  - Filtering by Status
  - Inline status updates
<img width="1070" height="500" alt="Screenshot 2025-07-16 at 2 36 01 AM" src="https://github.com/user-attachments/assets/2dcec444-f3fc-4c51-9186-8c7ba065bf41" />
    

- 🔁 **Automation Flows**:
  - 📩 Confirmation Email to user on submission
    <img width="500" height="700" alt="IMG_6125" src="https://github.com/user-attachments/assets/fdab6c96-0e20-4dd7-af31-03f3b6e0567f" />
    
    <img width="1470" height="700" alt="Screenshot 2025-07-16 at 12 52 06 AM" src="https://github.com/user-attachments/assets/13273a77-d351-483c-b4a3-7928ffbd8562" />


  - ⏱ Reminder Email to admin if unresolved after 2 days

    <img width="1470" height="700" alt="Screenshot 2025-07-16 at 1 32 57 AM" src="https://github.com/user-attachments/assets/9f25ad59-0257-4cd8-a87e-078e95676089" />

    

- 📊 **(Optional) Power BI Dashboard**:
  - Disputes by Card Type
  - Average Resolution Time
  - Total Open Cases

- 🔐 **Azure AD Authentication**:
  - Only logged-in users can submit/view
  - Personalized greeting via `User().FullName`
 
    <img width="1470" height="700" alt="Screenshot 2025-07-16 at 2 08 22 AM" src="https://github.com/user-attachments/assets/5bc1a26a-1168-4473-b9de-44227925b09d" />


    

---

