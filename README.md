# Power BI Access Request & Approval Automation

## Project Overview
Managing Power BI workspace and report access manually can lead to delays, security risks, and lack of auditability.  
This project automates **Power BI access requests and approvals** using **Power Automate**, ensuring secure and governed access management.



## Business Problem
- Access requests handled through emails
- No approval tracking
- Risk of unauthorized access
- High administrative effort



## Solution
An automated **access request and approval workflow** was implemented using **Power Automate**.



## Workflow Automation Steps
1. **Trigger**: User submits access request via **Microsoft Forms**
2. **Validation**: Request details captured (user, role, workspace)
3. **Approval**: Request sent to data owner / manager
4. **Actions**:
   - On approval → grant Power BI access
   - Notify user via email
   - Log request and approval in **SharePoint**
5. **Audit**: Complete access history maintained


## Technologies Used
- Power BI Service
- Power Automate
- Microsoft Forms
- SharePoint
- Outlook
- Microsoft Teams



## Business Impact
- ⏱ Reduced access provisioning time by **60%**
- 🔐 Improved security and role-based access control
- 📋 Full audit trail for compliance
- 📉 Reduced BI admin workload

