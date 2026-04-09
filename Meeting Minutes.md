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

# Meeting Minutes: Second Meeting with Supervisor

**Date:** Wednesday, 1 April 2026
**Time:** 16:30 – 17:30
**Participants:** Carrie Shi, Qinyi Zheng, Xiaonan Wang, Zhenhao Hong, Muchuan Ji, Navid
**Location:** In-person meeting at Melbourne Connect

---

## 1. Project Status & Administrative Issues
* **Onboarding Progress:** The team has successfully submitted legal names and emails as required for the onboarding process.
* **NDIS Screening Check Obstacle:** The organisation sent a screening check request (NDIS Worker Screening Check) that includes a $135 fee per person. 
    * **Action Item:** The group agreed not to pay this fee. Navid (Supervisor) will raise this with the course coordinator (Ian) for clarification, as students should not be expected to incur these costs.
    * **Reporting:** This bottleneck will be officially included as an issue in the upcoming Project Status Report.
* **Working Rights:** Evidence of working rights is also required as part of the screening process and must be provided by the team.

## 2. Organisation Background & Project Scope
* **Client Profile:** The project involves Wintringham, an organisation supporting elderly homeless people transitioning into end-of-life care. 
* **Project Understanding:** The team discussed Wintringham’s "Model of Care" and the continuum of care they provide.
* **Primary Goals:**
    * Centralise and link disparate datasets currently scattered across various government-funded services.
    * Provide an evidence-based report to validate the "Model of Care" to help secure continued government funding.
    * Analyse client transitions and outcomes to determine which specific supports have the most significant impact.

## 3. Data Access & Technical Roadmap
* **Data Bottleneck:** The team currently has zero access to the data, which is delaying the commencement of exploratory analysis.
* **Immediate Strategy:** * Request a "demo" or sample version (e.g., a mock-up or 5 rows of data) during the client meeting on **2 April** to understand column structures.
    * Early data access is prioritised to allow the team to progress with the analysis.
* **Exploratory Data Analysis (EDA):** Once data is received, the focus will be on EDA, including age distributions, gender ratios, and general methodologies.
* **Tooling:** * **Communication:** Internal updates via Slack and WeChat.
    * **Code Management:** GitHub will be used for code, but strictly **no data** is to be uploaded to the repository.

## 4. Reporting & Upcoming Timeline
* **Status Report:** The Week 6 Project Status Report was reviewed and refined during the meeting; it is due for submission to the course coordinator tomorrow.
* **Meeting Cadence:**
    * **Internal/General:** Weekly meetings are scheduled for **Tuesdays from 1:00 PM to 2:00 PM**.
    * **Supervisor Meeting:** Weekly meetings with the academic supervisor are set for **Fridays at 3:00 PM**.
* **Holiday Note:** Next week is a non-teaching week; no formal meeting will be held.
* **Future Planning:** A potential meeting with subject coordinators may be required in Week 9 or 10 to address delays caused by limited data access.


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
| Submit NDIS Worker Screening applications and report progress | Student Team | Early next week |
| Send the Project Brief to John for technical context | Tanya | Early next week |
| Send out the meeting invitation for next Thursday | Carrie | Early next week |

---

## 5. Next Meeting

* **Schedule:** Thursday, 9 April 2026.
* **Agenda:** Review specific data queries, follow up on screening submissions, and refine the ETL planning based on the project brief.

# Meeting Minutes: Brainstorming of matching name in different database

**Date:** April 8, 2026, 13:00 - 14:00
**Participants:** Student Team Members
**Location:** Student Connect Building

**Introduction:** Conducted a brainstorming session regarding the matching of records across various databases. There were suggestions to perform matching based on addresses, as well as proposals to develop a custom similarity algorithm.

# Meeting Minutes: Project Onboarding and IT Coordination

**Date:** April 9, 2026, 13:00 - 13:30
**Participants:** Carrie and other Student Team Members
* Ben 
* David E and N
* Tanya
* *Absent:* John (on leave)
**Location:** Online via Teams
---

## 1. Introductions
* Ben was introduced as the IT Service Delivery Manager. He, along with David and John, will be the primary contacts for infrastructure, access control, and technical support.
* Depending on the office schedule, students may interact with various members of the IT team for setup.

## 2. Compliance and Screening
* **Worker Screening (NDIS):**  Due to organizational structure and funding, all participants must undergo NDIS worker screening.
* **Reimbursement:** Wingtriham will reimburse the cost of the screening. 
    * **Action:** Students are to start the application process immediately.
    * **Requirement:** Provide the **submission receipt** to Wingtriham to trigger the reimbursement process.
* **Supplementary Document:** A new document regarding access to sensitive, non-de-identified personal data needs to be signed. This is in addition to the standard university agreement.

## 3. IT Setup and Systems
* **System Questions:** 
    * Technical questions will be handled by John or the IT team upon John's return next week.
* **Hardware Onboarding:** Once the screening is initiated and documents are signed, students must visit the office with their laptops for initial configuration.
* **Reimbursement Method:** It was noted that reimbursements for the screening costs will be provided in cash during the office visit.

## 4. Next Steps & Scheduling
* **Availability:** The regular Thursday slot may no longer work for everyone due to new work commitments. 
* **Action:** Carrie will send over updated availability to reschedule next week's sync-up.

---

## Action Items
| Task | Owner | Status |
| :--- | :--- | :--- |
| Start NDIS Worker Screening | Student Team | Pending |
| Submit screening receipts for reimbursement | Student Team | Pending |
| Sign supplementary data access document | Student Team | Pending |
| Provide written answers to high-level questions | Tanya | In Progress |
| Schedule laptop setup office visit | IT Team / Students | To be scheduled |
| Reschedule next week's meeting | Carrie | Pending |

