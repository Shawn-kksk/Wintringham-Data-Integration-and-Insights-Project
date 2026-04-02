# Meeting Minutes: Wintringham Data Integration and Insights Project First Meeting

**Date:** 12 March 2026  
**Time:** 16:00 - 17:00
**Location:** Online via Zoom  

---

### 1. Attendees

* **Present:** Carrie Shi, Qinyi Zheng, Xiaonan Wang, Zhenhao Hong, Navid Akhavan Attar(Supervisor)
* **Apologies:** Muchuan Ji

### 2. Agenda

* Introduction of team members and supervisor.
* Review of the project proposal.
* Discussion of the project schedule and timeline.

### 3. Discussion Summary

The team held an in-depth discussion regarding the technical stack and core project goals. The supervisor recommended organizing an early meeting with the project leads at Wintringham to finalize specific implementation details and requirements.

### 4. Key Decisions

* **Stakeholder Engagement:** Arrange a meeting with the industry partner (Wintringham) as soon as possible.
* **Meeting Cadence:** Establish a recurring weekly meeting to track progress.



# Meeting Minutes: Wintringham & University of Melbourne Project Kick-off

**Date:** March 26, 2026  
**Time:** 11:00 - 12:00
**Location:** Wintringham Office, Melbourne  

---

## 1. Attendees

### Wintringham Staff
- **Tanya Atkinson:** Acting GM for Quality, Innovation, and Communications.
- **David E:** Head of Information Technology.
- **David N:** Head of Practice for Social Support.

### University of Melbourne Student Team
Carrie Shi, Qinyi Zheng, Xiaonan Wang, Zhenhao Hong, Muchuan Ji

### Academic Supervisor
- **Navid:** PhD student / Project Supervisor (joined via video call)

---

## 2. Project Overview & Objectives

### Context
Wintringham is a non-profit organization specializing in housing and support for elderly people who have experienced homelessness. Historically, IT investment has been secondary to client care, leading to fragmented data systems.

### Core Objectives
* **System Integration:** Suggest ways to bridge at least seven disparate client databases that currently do not communicate.
* **Client Journey Mapping:** Transition from anecdotal stories to data-driven narratives, tracking client progress from homelessness to residential care over the last 10+ years.
* **Insight Reporting:** Identify which support services are most effective and provide a high-level overview of the total client population.

---

## 3. Key Challenges & Constraints

* **Data Silos:** Clients often exist in multiple databases with different IDs and inconsistent data collection methods.
* **Data Maturity:** The organization is in the early stages of viewing data as a strategic asset.
* **Privacy & Security:** The project involves sensitive **health and medical record data**. 
    * Full access to identified data (names, DOB) is required for effective linking.
    * Remote access will be managed via MDM (Mobile Device Management) software to ensure a secure "walled garden" environment.

---

## 4. Action Plan & Next Steps

| Task | Responsibility | Deadline |
| :--- | :--- | :--- |
| Send personal contact info (Email/Phone) | Students | ASAP |
| Internal onboarding & IT identity creation | Wintringham IT | Next week |
| Privacy & Ethics briefing | David E / Team | Next meeting |
| Project Status Report | Students | 1 Month |
| Final Semester 1 Presentation/Report | Students | 2 Months |

---

## 5. Communication & Cadence

* **Primary Channel:** A dedicated **Microsoft Teams** channel will be established for asynchronous communication and documentation.
* **Meeting Frequency:** * **Phase 1:** Weekly meetings to bridge the knowledge gap in data science and domain logic.
    * **Phase 2:** Transition to fortnightly meetings as the project stabilizes.
* **Next Meeting:** **Thursday, April 2, 2026, at 1:00 PM** (Online).

# Meeting Minutes: Royal Dental Hospital Project

**Date:** Wednesday, April 1, 2026
**TIme:** 16:30-17:30
**Participants:** Carrie Shi, Qinyi Zheng, Xiaonan Wang, Zhenhao Hong, Muchuan Ji, Navid
**Location:** In-person meeting in Melbourne Connect

---

## 1. Project Status & Administrative Issues
* **Onboarding Progress:** The team has submitted legal names and emails as required.
* **Screening Check Obstacle:** The organization sent a screening check request that includes a $135 fee per person.
* **Action Item:** The group will not pay this fee. The supervisor will email the course coordinator (Ian) to address this, as students should not be expected to pay for these checks. 
* **Working Rights:** Evidence of working rights is also required as part of the screening process.

## 2. Organization Background & Project Scope
* **Client Profile:** The company supports elderly homeless people transitioning into end-of-life care.
* **Data Challenge:** Data is currently scattered across various government-funded services with no central link.
* **Primary Goals:**
    * Centralize and link the disparate data sets.
    * Provide an evidence-based report to prove their "model of care" works to help secure government funding.
    * Analyze which specific supports have the most impact on clients.

## 3. Data Access & Technical Roadmap
* **Bottleneck:** The team currently has zero access to the data, which is delaying the start of exploratory analysis.
* **Immediate Strategy:** * Request a "demo" or sample version (e.g., 5 rows of data) to understand the column structure and start brainstorming.
    * Focus on **Exploratory Data Analysis (EDA)** once data is received, including age distributions and gender ratios.
* **Tooling:** The team is using **Slack** and **WeChat** for internal communication and **GitHub** for code (though no data is to be uploaded to GitHub).

## 4. Upcoming Timeline
* **Status Report:** A progress report for the course coordinator is due tomorrow.
* **Next Meeting:** Weekly meetings are set for Tuesdays from 1:00 PM to 2:00 PM.
* **Holiday Note:** Next week is a non-teaching week; no formal meeting will be held.


# Meeting Minutes: Wintringham Data Planning

**Date:** 2 April 2026  
**Time:** 13:00 - 14:00
**Location:** Online Meeting via Teams
**Participants:**
* **Wintringham Team:** Tanya (Chair), John (Senior Applications Analyst), David
* **Student Team:** Carrie and team members

---

## 1. Compliance and Onboarding

* **NDIS Worker Screening:** This is currently the primary bottleneck for the project placement. It was clarified that the placement can commence once the screening application has been **submitted**; the team does not need to wait for the final government clearance to begin work.
* **COVID-19 Vaccination Records:** As students will not be frequently in the office or in direct contact with clients, there is a greater degree of flexibility regarding vaccination evidence. Students who cannot access their official digital records should send an email stating the dates and locations of their vaccinations.

---

## 2. Project Objectives and Scope

* **Client Journey Mapping:** The project aims to understand the journey of Wintringham clients across various service stages.
* **Data Integration:** The goal is to link data across multiple disparate systems to create a "Golden Record" or a consolidated client view. This will support a narrative around the continuum of care and help analyse service patterns and outcomes.
* **Initial Exploration:** The first two months of the placement will be an exploratory phase to assess what data is available and determine if the proposed analysis is realistic.

---

## 3. Technical Discussion and Infrastructure

* **Systems Environment:**
    * **Azure Data Factory:** Used for data integration and ETL processes.
    * **SQL Servers & Data Warehouse:** The primary storage for core datasets.
    * **Business Systems:** Client records are held in systems including Epicor, LeeCare, and Chintaro.
* **Data Matching Logic:**
    * Primary matching attributes include Name, Date of Birth, and Address.
    * Challenges include inconsistent name formats (e.g., "Nicholas" vs "Nick") and address changes.
    * The team discussed the need for a strategic matching approach, potentially combining deterministic and probabilistic methods.
* **Student Tools:** The student team suggested using MySQL for local data processing and linking during the brainstorming phase.

---

## 4. Action Items

| Task Description | Assigned To | Due Date |
| :--- | :--- | :--- |
| Email specific data requirements (system types, sample columns) to Tanya and John | Carrie | ASAP |
| Submit NDIS Worker Screening applications and report progress | Student Team | Early next week |
| Send the Project Brief to John for technical context | Tanya | ASAP |
| Send out the meeting invitation for next Thursday | Carrie | ASAP |

---

## 5. Next Meeting

* **Schedule:** Thursday, 9 April 2026.
* **Agenda:** Review specific data queries, follow up on screening submissions, and refine the ETL planning based on the project brief.

