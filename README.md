# 🏦 Loan Application & Review Automation System

<p align="center">
  <img src="Images/ChatGPT%20Image%20Mar%202%2C%202026%2C%2009_36_29%20AM.png" alt="Loan Application Automation Banner" width="100%">
</p>

---

## 🌐 Overview

An end-to-end digital loan processing solution built using Microsoft Power Platform to streamline submission, approval workflows, status tracking, and stakeholder communication.

This system transforms a traditionally manual, email-driven process into a structured, automated, and auditable workflow.

---

## 🧠 Business Problem

Traditional loan processing often results in:

- Delayed approvals  
- Poor visibility into application status  
- Lack of audit traceability  
- Manual document validation  
- Fragmented stakeholder communication  

This solution digitizes and automates the full lifecycle.

---

## 🏗️ Solution Architecture

The system consists of:

### 👤 Public Loan Submission (Canvas App)
- Structured loan form
- Auto-generated unique Loan ID
- PDF-only validation
- Default status assignment
- Clean user experience

### 🏢 Internal Review Interface (Model-Driven App)
- Application review queue
- Controlled status transitions
- Applicant history tracking
- Admin filtering capabilities

### 🔄 Automation Layer (Power Automate)
- Status change email notifications
- Audit log creation
- Approval workflow triggers
- LoanStatusHistory tracking

### 🗄️ Dataverse Data Model
Core tables:
- LoanApplication
- LoanDocuments
- LoanStatusHistory
- Reference Data

---

## 📊 Dashboard & Monitoring

- Total Applications KPI
- Pending Review KPI
- Approval vs Rejection distribution
- Application trend visualization
- Interactive filtering

---

## 📦 Repository Contents

- Full Power Platform Solution Export
- Canvas App source file (.msapp)
- Power Automate flow exports
- Architecture diagrams
- Screenshots
- Executive presentation deck
