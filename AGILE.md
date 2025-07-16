# 🚀 AGILE.md – Agile Tracking for DisputePortal

## 📌 Project Name
**DisputePortal – Transaction Dispute Resolution System**

## 🧩 Agile Methodology
This project uses the Agile process model with user stories, sprint tasks, and a Kanban board for iterative development and tracking in Azure DevOps.

---

## 📋 USER STORIES

### 🟦 US-001 – Dispute Submission
**As a user**, I want to submit a dispute with all required details (Transaction ID, Reason, Evidence) so that it can be processed.

- [x] Design UI form in Power Apps
- [x] Add input controls (text, dropdowns, attachments)
- [x] Enable Azure AD login
- [x] Submit logic using `Patch()`

---

### 🟦 US-002 – Confirmation Email to User
**As a user**, I want to receive a confirmation email after submitting a dispute.

- [x] Create SharePoint list: `DisputeRecords`
- [x] Create Power Automate Flow: DisputeConfirmation
- [x] Format dynamic email with submitted data

---

### 🟦 US-003 – Reminder if Unresolved
**As an admin**, I want to be reminded if a dispute is still pending after 2 days.

- [x] Create Flow: DisputeReminder
- [x] Add Delay action (2 days)
- [x] Add Get Item + Condition (Status = "Pending")
- [x] Send escalation email

---

### 🟦 US-004 – Dashboard Analytics
**As a manager**, I want to visualize dispute volumes and resolution times to track trends.

- [ ] (Optional) Build Power BI dashboard
- [ ] Import data from SharePoint list
- [ ] Create charts (Disputes by CardType, Avg. resolution time)

---

### 🟦 US-005 – GitHub Repo with Docs
**As a developer**, I want to publish all documentation and visuals to GitHub.

- [x] Create folder structure: `/docs`, `/screenshots`, `/flows`
- [x] Add README.md and AGILE.md
- [x] Push final code with video + screenshots

---

## 🚦 SPRINT STRUCTURE

| Sprint | Goals |
|--------|-------|
| Sprint 1 | Power Apps form + SharePoint integration |
| Sprint 2 | Power Automate Flows (confirmation + reminder) |
| Sprint 3 | GitHub repo setup + docs + Agile board |
| Sprint 4 (Optional) | Power BI dashboard + embedding |

---

## 📌 Azure DevOps Board Setup

### Board Columns:
- 🔵 **To Do**: All pending tasks
- 🟡 **In Progress**: Current sprint items
- 🟢 **Done**: Completed features (submitted and tested)

---



