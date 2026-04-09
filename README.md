# 🚀 Horizon National Bank (HNB) – Digital Loan Origination System (DLOS)

## 📌 Overview
This Project demonstrates an end-to-end Business Analysis transformation of a traditional, manual Personal Loan Application process into a fully digital, automated system.
The objective was to identify inefficiencies in the current (AS-IS) process and design a scalable, customer-centric TO-BE Digital Loan Origination System (DLOS).

![Loan Process Flow](executive_summary/executive_summary.png)
________________________________________

## 🎯 Problem Statement
The existing loan application process at HNB is heavily manual, fragmented, and time-consuming, leading to:
•	⏱ Long processing times (7–14 days)
•	📄 Paper-based application and document handling
•	🔁 Redundant data entry across multiple systems
•	📞 High operational overhead due to status inquiries
•	🐢 Delays in credit checks and underwriting decisions

🔍 Approach
This Projects follows a structured Business Analysis framework:
1.	AS-IS Process Mapping
2.	Pain Point Identification
3.	Gap Analysis
4.	Requirement Prioritization (MoSCoW)
5.	TO-BE Process Design
6.	Solution Definition & Capability Mapping


![Loan Process Flow](process_flows/Loan_Process_Flow.png)
________________________________________

## 🧩 AS-IS Process (Current State)

The current process involves multiple manual steps across stakeholders:
•	Customer visits branch and fills a 12-page form
•	Physical document submission and verification
•	Manual data entry into LOS and CRM systems
•	Email-based credit bureau requests
•	Underwriting committee delays (3–5 days)
•	Physical communication via postal letters
📌 Key Insight:
The process is fragmented, lacks integration, and is dependent on manual intervention at every stage.

![Loan Process Flow](process_flows/ASIS_pain_points.png)

________________________________________

## 🧠 Prioritization (MoSCoW Framework)

✅ MUST HAVE
•	Digital application form
•	Credit bureau API integration
•	Document upload with OCR
•	Decisioning engine
•	Loan officer dashboard
⚡ SHOULD HAVE
•	SMS/Email notifications
•	Application status tracker
💡 COULD HAVE
•	Mobile-native application
❌ WON’T HAVE
•	Blockchain-based document verification

![Loan Process Flow](product_design/MoSCoW.png)
________________________________________

## 🔄 TO-BE Process (Future State)

The redesigned process enables a seamless digital journey:
•	Customer applies online via web/app
•	Uploads documents digitally (OCR-enabled)
•	System performs instant credit checks via API
•	Automated decisioning engine processes application
•	Real-time status updates provided to customer
•	E-signature completes the process without branch visits
📌 Key Outcome:
A fully digital, integrated, and automated loan origination workflow.

![Loan Process Flow](process_flows/TO_BE_Strengths.png)

________________________________________

## 👥 Stakeholder Identification & Importance

Key stakeholders are identified based on their power and interest in the project, guiding engagement strategy. High-power, high-interest stakeholders are closely managed, while low-power/low-interest stakeholders are monitored. This ensures effective communication and prioritization throughout the project lifecycle.
![Loan Process Flow](stakeholder_analysis/stakeholder_matrix.png)

________________________________________

## Swimlane Description of the Future State
Swimlane Description of the Future State. Customers apply via HNB website/app with an intelligent, multi-step wizard; documents are uploaded digitally, and data auto-populates for existing users. Automated credit checks and a decision engine handle approvals, referrals, or declines instantly, while loan officers review edge cases through a dashboard. Customers sign agreements electronically and track status 24/7.

![Loan Process Flow](product_Design/process_flow_diagram.png)

________________________________________

## Context Diagram (DFD Level 0) – System Boundary

The DLOS is treated as a single “black box” system interacting with external entities. Customers submit applications and documents, receive status updates, and e-sign agreements. External systems like Experian/Equifax, FiServ Core Banking, OpenText DMS, DocuSign, and Twilio/SendGrid exchange credit data, profile info, documents, and notifications. Loan officers interact internally to review, annotate, and make decisions.

![Loan Process Flow](product_Design/system_integration_diagram.png)
________________________________________

## ⚡ Importance of JIRA & Kanban

JIRA with Kanban boards streamlines project tracking, visualizes workflow, and helps teams prioritize tasks efficiently. It ensures transparency, accountability, and faster delivery by clearly showing work in progress, bottlenecks, and completed tasks.


![Loan Process Flow](Agile_Delievery/JIRA_Board%20_Kanban.png)
________________________________________

## 🧾 Key Deliverables
•	AS-IS & TO-BE Swimlane Diagrams
•	Pain Point Analysis Dashboard
•	Gap Analysis Matrix
•	Stakeholder Register
•	RACI + Communication Plan
•	MoSCoW Prioritization
•	Epic Planning
•	Sprint Planning
•	User Stories & Functional Requirements
________________________________________

## 🛠 Tools & Techniques Used
•	Figma (Process flows & visualizations)
•	MoSCoW Prioritization
•	Gap Analysis
•	Stakeholder Analysis
•	Process Modeling (Swimlanes)
________________________________________

## 💡 Key Learnings
•	Digital transformation requires both process redesign and system integration
•	Identifying root causes is critical before proposing solutions
•	Prioritization frameworks ensure focused and realistic delivery
•	Customer experience is a key driver in modern system design
________________________________________

## 📂 Repository Structure

/Agile_Delievery → Epics + US planning, kanban board
/Business Documents → BRD, Agile Release Roadmap
/Executive Summary → Executive Summary
/process_flows → AS_IS Process, TO_BE Process, Loan Process Flow
/Product Design → MoSCoW Priroitization, System Integration, Process Flow
/Stakeholder Analysis → Stakeholder matrix, Stakholder Context, RACI + Communication Plan, Stakeholder Register
________________________________________