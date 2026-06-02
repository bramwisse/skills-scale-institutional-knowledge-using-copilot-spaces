# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management process documentation. This folder contains comprehensive guides for managing projects across all phases of the product delivery lifecycle.

## Quick Overview of OctoAcme Project Management Processes

### Structured Lifecycle & Core Principles

OctoAcme follows a structured five-phase project lifecycle designed to balance iterative delivery with stakeholder alignment. Projects move through **Initiation** (validating business need and securing sponsor buy-in), **Planning** (breaking work into shippable increments with clear acceptance criteria), **Execution** (daily delivery with continuous testing and tracking), **Release** (standardized deployment to production), and **Close & Retrospective** (capturing learnings for continuous improvement). This approach is grounded in five core principles: customer-first prioritization, iterative delivery of small testable increments, clear ownership through named Project Managers and Product Leads, data-informed decision-making, and psychological safety to encourage team feedback.

### Roles, Responsibilities & Communication Cadence

OctoAcme defines clear accountability through four key personas. **Developers** implement features, write tests, and participate in design reviews while helping identify technical risks. **Product Managers** define what to build by creating problem statements, prioritizing backlogs, and measuring outcomes through success metrics. **Project Managers** coordinate delivery by managing schedules, risks, dependencies, and ensuring consistent documentation and stakeholder communication. **Stakeholders** provide inputs and approvals at key gates. Communication happens through a structured rhythm: weekly syncs between PM and Product Manager, twice-weekly team standups (15 min daily standups during execution), monthly stakeholder updates, and ad-hoc escalations. The escalation path for blockers progresses from team-level triage → PM escalation to Product Lead → sponsor-level escalation for business-impacting issues.

### Execution, Quality & Release Standards

During the Execution phase, teams work through a GitHub Projects-based workflow with columns spanning Backlog → Ready → In Progress → In Review → QA → Done. Pull requests follow strict conventions: limited to ≤400 lines, include issue links and acceptance criteria, require automated CI testing and linting, and mandate at least one approval before merging. Quality assurance is comprehensive, including unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance. Release management is equally rigorous, with pre-release requirements including all acceptance criteria met, passing CI/security scans, documented rollback plans, and smoke tests prepared. The team tracks velocity and burndown, monitors success metrics via dashboards, and maintains an updated risk register reviewed weekly.

### Risk Management & Continuous Improvement

OctoAcme treats risk management as an ongoing discipline rather than a one-time activity. Risks are captured in a simple register tracking ID, description, impact/likelihood, owner, mitigation plan, and status—reviewed continuously during weekly syncs. Stakeholder communication leverages a single source of truth (project README or release doc) with standardized templates for weekly status updates and incident communications. After each sprint, release, or significant milestone, the team conducts blameless retrospectives to capture what went well, what could improve, and generate 2–3 prioritized action items with clear owners and timelines. This structured approach to learning ensures that process improvements are tracked, measured for impact, and celebrated, embedding continuous improvement into the team's culture rather than treating it as an afterthought.

---

## Process Documentation Files

- **[octoacme-project-management-overview.md](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, and key artifacts
- **[octoacme-project-initiation.md](octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create an initial plan
- **[octoacme-project-planning.md](octoacme-project-planning.md)** — How to turn an approved initiative into an actionable backlog and delivery plan
- **[octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution, testing, and progress tracking
- **[octoacme-risks-and-communication.md](octoacme-risks-and-communication.md)** — Risk identification, management, and stakeholder communication strategies
- **[octoacme-release-and-deployment.md](octoacme-release-and-deployment.md)** — Standardized processes for releasing features to production
- **[octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md)** — How to capture learnings and convert them into actionable improvements
- **[octoacme-roles-and-personas.md](octoacme-roles-and-personas.md)** — Detailed definitions of typical roles and responsibilities

---

## How to Use These Docs

- **New team members:** Start with [octoacme-project-management-overview.md](octoacme-project-management-overview.md) for a complete picture of how OctoAcme operates.
- **Project kickoff:** Reference [octoacme-project-initiation.md](octoacme-project-initiation.md) and [octoacme-project-planning.md](octoacme-project-planning.md) to set up your project correctly.
- **Day-to-day execution:** Use [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md) as your operating manual during the delivery phase.
- **Risk & escalations:** Consult [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md) for how to identify and communicate risks.
- **Releases:** Follow [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md) to ensure consistent, safe deployments.
- **Learning & improvement:** Use [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md) to capture and act on team insights.
- **Role clarity:** Reference [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) to understand responsibilities and expectations.

---

## Contributing to Process Docs

To propose updates or new content for these process documents, [open an issue](https://github.com/bramwisse/skills-scale-institutional-knowledge-using-copilot-spaces/issues/new/choose) using the **"Add Content to Project Management Process Docs"** template. This ensures your suggestions are reviewed, validated with stakeholders, and incorporated consistently.
