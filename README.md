# Change Request Tracker Automation (n8n)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![n8n](https://img.shields.io/badge/Built%20With-n8n-orange.svg)


This project is an end-to-end Change Request approval workflow built using **n8n**, **Google Forms**, **Google Sheets**, and **Gmail**.

It automates the intake, tracking, approval, and notification of change requests in a PMO-style process.

---

## 🚀 Features

- Intake of change requests via Google Forms  
- Automatic detection of new requests using Google Sheets Trigger  
- Unique Request ID generation  
- Status initialization (Pending Approval)  
- Email-based approval workflow (Approve / Reject buttons)  
- Automated status updates in Google Sheets  
- Requester notification on approval or rejection  

---

## 🧠 Workflow Overview

1. User submits a Change Request via Google Form  
2. Response is stored in Google Sheets  
3. n8n detects the new row  
4. A unique Request ID is generated  
5. An approval email is sent to the approver  
6. Approver clicks Approve or Reject  
7. The corresponding row is updated in Google Sheets  
8. The requester is notified of the decision  

---

## 🛠️ Tech Stack

- n8n (Workflow Automation)
- Google Forms (Request Intake)
- Google Sheets (Request Register)
- Gmail (Approval + Notifications)

---

## 📂 Files

| File | Description |
|------|-------------|
| change-request-workflow.json | Exported n8n workflow |
| README.md | Project documentation |

---

## 🧪 How to Run This Project

1. Install and start n8n locally  
2. Import `change-request-workflow.json`  
3. Connect Google Sheets and Gmail credentials  
4. Create a Google Form linked to a Google Sheet  
5. Update the trigger node with your Sheet ID  
6. Publish the workflow  
7. Submit a form response  
8. Approve or reject via email  

---

## 💡 Use Cases

- PMO Change Request tracking  
- IT service request approvals  
- Internal process automation  
- Operations workflow automation  

---

## 📌 Author

**Aayush Pandey**

Built as a portfolio project to demonstrate workflow automation, approval flows, and PMO-style governance.
