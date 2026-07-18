# ProgramPilot AI

## See delivery risks before they become business failures

ProgramPilot AI is an AI-powered enterprise program observability and early-warning platform for Program Managers, Project Managers, PMO Leaders, Delivery Leaders, Transformation Leaders, and Executives.

It transforms fragmented program information into explainable risks, correlated warning signals, recommended decisions, and executive-ready insights.

---

## Hackathon Theme: Observability

Technical teams use observability platforms to monitor applications, infrastructure, logs, and system performance. Program Managers, however, often depend on spreadsheets, meetings, RAID logs, and manually prepared status reports to understand delivery health.

ProgramPilot AI brings observability to enterprise program execution.

> Technical teams observe systems. ProgramPilot AI helps leaders observe execution.

---

## The Problem

Program information is usually scattered across:

- Meeting transcripts
- RAID logs
- Project plans
- Status reports
- Milestone trackers
- Action logs
- Stakeholder communications
- Budget reports
- Capacity plans
- Cross-project dependencies

By the time leaders recognize a serious delivery risk, the milestone may already be delayed.

---

## The Solution

ProgramPilot AI converts fragmented project information into an explainable, real-time view of program health.

It helps leaders answer four questions:

1. What is changing?
2. Why is it changing?
3. What could happen next?
4. What action should be taken now?

Most project-management tools report what has already happened. ProgramPilot AI helps leaders anticipate what may happen next.

---

## Core Features

### 1. Program Command Center

A unified executive dashboard showing:

- Program Health Score
- Schedule and budget confidence
- Dependency health
- Team-capacity pressure
- Active alerts
- Upcoming milestones
- Overdue actions

### 2. Program Signal Stream

Monitors signals from meetings, RAID logs, milestones, actions, dependencies, budgets, capacity reports, and stakeholder updates.

### 3. AI Program Analyzer

Converts unstructured meeting notes and project updates into:

- Risks and issues
- Decisions and actions
- Owners and deadlines
- Dependencies
- Capacity constraints
- Schedule warnings

### 4. Early-Warning Engine

Each warning includes severity, confidence, supporting evidence, root-cause hypothesis, potential business impact, and a recommended intervention.

### 5. Signal Correlation

ProgramPilot AI connects weak signals that traditional reporting may examine separately.

Example:

- Vendor has not responded for five days
- Security approval remains pending
- Integration testing starts next week
- No contingency owner exists

The platform correlates these signals and identifies a material Release 3 delivery risk.

### 6. Explainable Program Health Score

The health score considers critical risks, delayed milestones, overdue actions, blocked dependencies, budget variance, capacity pressure, delayed decisions, and stakeholder responsiveness.

Every score change is explained. The application does not present an unexplained AI-generated number.

### 7. Program Trace View

Follows a business outcome across its dependency chain:

`Release 3 → Security Approval → Vendor Response → Integration Testing → User Acceptance Testing → Production Release`

### 8. AI Decision Assistant

Recommends the immediate action, responsible owner, suggested deadline, expected impact, confidence level, supporting evidence, and an alternative response.

### 9. Executive Report Generator

Creates a decision-ready steering update containing overall health, material changes, critical risks, delayed milestones, leadership decisions, recommended actions, and next seven-day priorities.

### 10. Program Intelligence Chat

Users can ask:

- Why did program health decline?
- What is threatening Release 3?
- Which dependency requires escalation?
- What changed this week?
- What decision must leadership make?
- What should I prioritize today?

### 11. Business Impact Dashboard

Displays prototype estimates for reporting time saved, risks detected early, delays potentially avoided, overdue actions identified, decisions accelerated, and estimated cost exposure.

---

## Three-Minute Judge Demo

The application includes a guided **Run Judge Demo** experience:

1. Project Orion begins with a health score of 82.
2. A new meeting update arrives.
3. ProgramPilot extracts multiple weak signals.
4. Signal Correlation identifies a critical dependency.
5. A Release 3 warning is generated.
6. Program health falls from 82 to 68.
7. The platform explains the 14-point decline.
8. The Decision Assistant recommends an escalation.
9. An executive steering update is generated.
10. The potential business impact is quantified.

---

## Demonstration Scenario

The MVP uses realistic sample data for **Project Orion**, an enterprise CRM-transformation program.

The primary scenario includes:

- Delayed vendor security approval
- Blocked integration testing
- Missing contingency ownership
- Engineering capacity exceeding 110%
- A predicted nine-day delay
- Estimated cost exposure of $420,000

Financial and time-based values are prototype estimates created for demonstration purposes.

---

## Technology

The GitHub Pages version is a lightweight browser-based application using:

- HTML5
- CSS3
- JavaScript
- Responsive web design
- Local browser storage
- Deterministic Demo Intelligence Mode

No API key or paid AI service is required to run the demonstration.

The product architecture can later integrate with OpenAI or Azure OpenAI, Microsoft Graph, Teams, Jira, Planner, SharePoint, portfolio-management platforms, and enterprise data sources.

---

## Run Locally

```bash
git clone https://github.com/subhankar4u/ProgramPilot-AI.git
cd ProgramPilot-AI
```

Open `index.html` in a modern browser and select **Run Judge Demo**.

---

## Deploy with GitHub Pages

1. Upload `index.html` and this `README.md` to the repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select the `main` branch and `/root` folder.
5. Click **Save**.

The expected URL is:

`https://subhankar4u.github.io/ProgramPilot-AI/`

---

## Future Roadmap

- Live AI document analysis
- Microsoft Teams and Outlook integration
- Jira and Microsoft Planner integration
- Portfolio-level observability
- Automated stakeholder-sentiment analysis
- Predictive schedule simulation
- Role-based access control
- PowerPoint and PDF report generation
- Enterprise knowledge retrieval using RAG

---

## Creator

**Subhankar Dey**

Global Program Manager | PMP-Certified Professional | AI Educator | Career and Communication Coach | Product Builder

Building practical AI-powered solutions for professionals, project teams, and enterprise leaders.

---

## Disclaimer

ProgramPilot AI is currently a hackathon MVP. Program-health calculations, predictions, financial exposure, and time estimates are prototype outputs intended for demonstration and product validation.

---

## Closing Thought

> Traditional reports explain what happened yesterday. ProgramPilot AI helps leaders protect what must happen tomorrow.
