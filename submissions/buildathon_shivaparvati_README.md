# HR Cost Intelligence Engine

> Know what your meetings are costing you — in real time.

## Overview

HR Cost Intelligence Engine is an AI-powered analytics platform that transforms calendar activity into actionable financial insights. By connecting meeting data with employee cost structures, the platform automatically attributes meetings to projects, calculates HR expenditure, and provides leadership with complete visibility into workforce utilization and project spending.

The system eliminates reliance on manual timesheets and uncovers hidden costs buried inside calendars.

---

## Problem Statement

Organizations track payroll and project budgets separately, creating a visibility gap in understanding how employee time translates into project costs.

### Challenges

* No real-time project-level HR cost tracking
* Inaccurate or incomplete timesheets
* Unused insights hidden within calendar data
* Difficulty identifying budget overruns and resource leakage

---

## Solution

The HR Cost Intelligence Engine automatically:

1. Integrates with Google Calendar and Outlook
2. Analyzes meeting metadata using AI
3. Attributes meetings to projects
4. Calculates meeting and project costs
5. Detects anomalies and cost overruns
6. Provides executive-level dashboards

---

## Key Features

### Calendar Integration

* Google Calendar Integration
* Microsoft Outlook Integration
* Meeting metadata extraction
* Historical meeting analysis

### AI Project Attribution

Uses:

* Meeting titles
* Descriptions
* Attendees
* Recurrence patterns
* Team participation

To automatically assign meetings to projects with confidence scores.

### Cost Intelligence

Automatically computes:

* Cost per meeting
* Cost per employee
* Cost per project
* Cost per department
* Monthly HR expenditure

### Executive Dashboard

Provides visibility into:

* Total Monthly Calendar Cost
* Average Cost per Meeting Hour
* Project Cost Distribution
* Budget vs Actual Spending
* Meeting Type Analysis

### Meeting Ledger

Detailed meeting-level breakdown including:

* Meeting title
* Duration
* Attendees
* Cost
* Project attribution
* Anomaly indicators

### Anomaly Detection

Flags:

* High-cost meetings
* Budget overruns
* Unattributed meetings
* Unusual employee allocation patterns

---

## Tech Stack

### Frontend

* React
* TypeScript
* Vite
* Tailwind CSS
* Zustand
* Recharts
* Framer Motion
* TanStack Table
* Lucide React

### Backend

* Node.js
* Express.js

### Database

* PostgreSQL

### AI Layer

* OpenAI API / Gemini API

### Authentication

* Google OAuth
* Microsoft OAuth

### Deployment

* Vercel (Frontend)
* Render / Railway (Backend)
* Neon PostgreSQL

---

## Application Modules

### Dashboard

Displays:

* Total Monthly Calendar Cost
* Average Cost per Meeting Hour
* Top Project Utilization
* Untagged Meetings

### Project Cost Analytics

Visualizations include:

* Budget vs Actual Cost
* Cost by Meeting Type
* Monthly Cost Trends

### Meeting Ledger

Tracks every meeting with:

* Project attribution
* Cost calculations
* Status indicators
* Anomaly detection

### Cost Configuration

Manage:

* Employee roles
* Hourly rates
* Salary bands
* Cost models

### AI Insights

Provides:

* Cost leakage analysis
* Overrun predictions
* Meeting efficiency scores
* Resource allocation recommendations

---

## Cost Calculation Logic

Meeting Cost Formula:

Cost = Duration × Sum(Employee Hourly Rates)

Example:

Meeting Duration = 2 Hours

Attendees:

* Senior Engineer = $85/hr
* Product Manager = $95/hr

Meeting Cost:

2 × (85 + 95) = $360

Project costs are calculated by aggregating all attributed meeting costs.

---

## Architecture

Google Calendar / Outlook

↓

Meeting Metadata

↓

AI Attribution Engine

↓

Project Mapping

↓

Cost Calculation Engine

↓

Dashboard & Analytics

---

## Demo Workflow

1. Connect Calendar
2. Import Meeting Data
3. Run Project Attribution AI
4. Review AI-assigned Projects
5. Analyze Costs Dashboard
6. Identify Cost Overruns
7. Generate Insights

---

## Future Enhancements

* Real-time calendar synchronization
* Predictive budget forecasting
* AI meeting efficiency scoring
* Slack and Microsoft Teams integration
* Department-level analytics
* Automated utilization reports

---

## Impact

HR Cost Intelligence Engine enables organizations to:

* Improve budget visibility
* Reduce resource leakage
* Eliminate manual timesheets
* Optimize meeting culture
* Increase project accountability

By turning calendar activity into financial intelligence, organizations gain complete visibility into where their people cost is actually going.

---

## Team

Built for Buildathon Hackathon

**Project:** HR Cost Intelligence Engine

**Tagline:** Know what your meetings are costing you — in real time.
