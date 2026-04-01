# OctoAcme Project Management Docs

This README provides an entry point and guide to OctoAcme's project management methodology. Our practices are modeled for SaaS product teams focused on iterative delivery, clarity of ownership, and customer value.

## Summary of Project Management Process

OctoAcme's project management framework is a structured, lifecycle-driven approach designed to convert business needs into high-quality software through five distinct phases: Initiation, Planning, Execution, Release, and Retrospective. The process begins with a **Project One-pager** to validate business needs and success metrics before moving into a detailed planning phase where work is broken down into shippable Sprint increments. This iterative delivery model emphasizes small, testable increments and clear ownership, ensuring that every project remains aligned with customer value while maintaining a manageable scope.

The framework is powered by four core personas: **Product Managers (PdM)**, who define the "what" and prioritize the backlog; **Project Managers (PM)**, who coordinate delivery, schedules, and risk; **Developers**, who implement features and maintain technical quality; and **QA/Testing**, who validate acceptance criteria. Communication is handled through a tiered cadence, including daily standups for execution tracking, weekly delivery syncs to flag risks, and monthly stakeholder updates. This is complemented by a robust risk management strategy where potential blockers are tracked in a Risk Register and escalated through defined levels—from team-level triage up to sponsor-level intervention for business-impacting issues.

Quality assurance and execution are governed by a strict **Definition of Done** and a mandatory Pull Request (PR) workflow. New logic must be covered by unit tests, while integration and end-to-end smoke tests are required for critical flows before any production release. OctoAcme prioritizes observability and security, integrating automated scanning and linting directly into the CI/CD pipeline. The release process itself is highly standardized, requiring pre-release checklists, rollback playbooks, and post-deployment verifications to minimize production risk.

To foster a culture of continuous improvement, OctoAcme concludes every milestone with a structured retrospective. These sessions focus on identifying actionable improvements which are then fed back into the project backlog as tasks with clear owners. This **living documentation** approach, supported by specialized GitHub Issue templates for process updates, ensures that tacit team insights are captured, versioned, and standardized—reducing single-person dependency and accelerating onboarding for new team members.

## Process Documents

- [**OctoAcme Project Management Overview**](octoacme-project-management-overview.md): Principles, roles, lifecycle, and how docs fit together.
- [**Project Initiation Guide**](octoacme-project-initiation.md): From idea to greenlight, one-pager template.
- [**Project Planning**](octoacme-project-planning.md): Turning initiatives into sprints and actionable plans.
- [**Execution & Tracking**](octoacme-execution-and-tracking.md): Daily/weekly rhythm, tracking, and QA.
- [**Risks & Communication**](octoacme-risks-and-communication.md): Managing risks, communication, escalation.
- [**Release & Deployment**](octoacme-release-and-deployment.md): Releasing safely, mitigation, rollback, and notes.
- [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md): Running retros, tracking action items.
- [**Roles & Personas**](octoacme-roles-and-personas.md): What different roles do and how they're used.

All process documents are maintained as living knowledge and should be updated as practices improve.
