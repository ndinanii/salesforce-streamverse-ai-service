# StreamVerse: AI-Powered Customer Service & Case Deflection

This project addresses a customer retention crisis at a video streaming service by designing a scalable support ecosystem that uses AI and automation to deflect simple cases and intelligently route complex issues.

## 1. Business Challenge

A 48-hour customer service response time was causing unacceptable levels of churn (cancellations). The 15 support agents were overwhelmed by a chaotic, un-triaged system, leading to poor customer satisfaction.

## 2. My Role & Strategic Solution

As a Junior Salesforce Strategist, I designed a **scalable support ecosystem** to transform the team from a reactive "fire department" into a proactive, efficient, and customer-centric retention force.

### Phase 1: Implement a "Layered Defense" for Case Deflection

- **Business Goal:** Immediately reduce the 5,000+ daily case volume.
- **Platform Strategy:** Deployed a two-pronged deflection strategy:
    - **Knowledge Base (Self-Service):** Published high-quality articles for the top 10-20 common questions, empowering customers to solve their own problems.
    - **Einstein Bot (Guided Service):** Deployed a bot to handle the top 3-5 transactional requests (e.g., "Reset my password") without human intervention.

### Phase 2: Establish "Intelligent Triage & Routing"

- **Business Goal:** For cases requiring a human, eliminate the 48-hour wait and stop incorrect routing.
- **Platform Strategy:**
    - **AI Case Classification:** Used AI to *instantly* read and categorize incoming cases (e.g., "Billing," "Technical").
    - **Omni-Channel Routing:** Used the AI classification to route the case via Omni-Channel to an agent who was both available and skilled in that category.

### Phase 3: Empower Agents & Measure Success

- **Business Goal:** Give agents the tools for first-contact resolution and provide management with visibility into KPIs.
- **Platform Strategy:**
    - **Service Cloud Console:** Configured a 360-degree view of the customer to eliminate "swivel-chairing."
    - **Service Analytics:** Deployed a dashboard focused on key business metrics: **First Response Time (FRT)**, **Case Resolution Time**, and **CSAT**.

## 3. Strategist's Note

> This solution prioritizes scalability and efficiency. By using AI (Bots, Classification) to handle high-volume, low-complexity work, we freed skilled agents to focus on high-value, complex interactions. This "clicks-not-code" strategy directly attacks the root cause of churn and has an immediate impact on service KPIs.

---

## 4. Engineering Philosophy: The Colt Protocol

This project follows **The Colt Protocol** methodology, a systematic 6-stage approach to Salesforce development:

### The 6-Stage Pipeline

1. **Requirements Elicitation (The "Why" & "What")** - Define goals, personas, and Definition of Done (DoD)
2. **User-Centric Design (The "Look & Feel")** - Strict adherence to Lightning Design System (SLDS)
3. **Business Process Mapping (The "Flow")** - Synchronous vs. Asynchronous processing decisions
4. **Data Modeling & ERD (The "Skeleton")** - Security-first schema design with OWD and sharing rules
5. **Defining Testable Criteria (The "Safety Net")** - Test-Driven Development (TDD) with 85%+ coverage
6. **Clear Documentation (The "Legacy")** - ApexDoc standards and structured project artifacts

### 📂 Project Documentation

Comprehensive documentation following The Colt Protocol is available in the `_documentation/` folder:

```
_documentation/
├── 00_Project_Brief/          # Project Charter & Stakeholder Register
├── 01_Requirements/           # User Stories & Functional Specs
├── 02_Design/                 # UX Wireframes, UI Mockups, SLDS Theme Map
├── 03_Architecture/           # Process Flows, ERD, Security Matrix
├── 04_Testing/                # Test Plan, Data Factory Spec, UAT Scripts
└── 05_Manuals/                # Admin Guide & User Guide
```

### Salesforce Best Practices Applied

- **AI-Powered Automation**: Einstein Bots and AI Case Classification for deflection
- **Omni-Channel Routing**: Skills-based routing with real-time capacity management
- **Service Console**: 360-degree customer view for first-contact resolution
- **Analytics**: Service KPIs dashboards (FRT, Resolution Time, CSAT)
- **Scalability**: Layered defense strategy to handle high case volumes
