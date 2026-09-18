# OctoAcme Project Management Docs

This directory contains the core project management guidance for OctoAcme. It provides a single, navigable entry point for how work is initiated, planned, delivered, released, and improved across projects.

## Project management approach

OctoAcme uses a customer-first, iterative, data-informed approach with clear ownership. Teams deliver small, testable increments, measure outcomes, and use evidence to guide decisions and improvements. The process documentation supports consistent execution while allowing teams to adapt practices to project needs.

## Project lifecycle

1. **Initiation** — Validate the business problem, define measurable success criteria, identify stakeholders, and decide whether the work should proceed to planning.
2. **Planning** — Turn approved work into a prioritized backlog with acceptance criteria, estimates, milestones, owners, dependencies, risks, and a documented Definition of Done.
3. **Execution** — Deliver incrementally using the project board, regular team communication, small pull requests, code review, automated checks, and appropriate testing.
4. **Release** — Confirm acceptance criteria and CI/security readiness, prepare release notes and rollback plans, deploy through staging and production controls, and verify the outcome.
5. **Retrospective and continuous improvement** — Review what went well and what could improve, assign action items, measure their impact, and carry learning into future work.

## Operating practices

- **Core roles:** Project Managers coordinate delivery, schedules, risks, and communications; Product Managers or Product Leads define outcomes and priorities; Developers build and test solutions; QA validates quality and acceptance criteria; stakeholders provide input and approvals.
- **Communication cadence:** Use standups, weekly PM and product alignment, delivery or milestone reviews, regular stakeholder updates, and escalation paths for blockers and risks.
- **Risk management:** Maintain a risk register with impact, likelihood, owner, mitigation, and status. Review risks and dependencies regularly and escalate from the team to the PM, Product Lead, or sponsor as appropriate.
- **Quality practices:** Use clear acceptance criteria and a Definition of Done; require unit, integration, or end-to-end testing where applicable; run CI, linting, and security checks; and perform manual QA or smoke tests when needed.
- **Delivery controls:** Track work through backlog, ready, in progress, review, QA, and done states. Keep pull requests small where possible, link them to issues, require review, and monitor success metrics, errors, latency, and usage.

## Document index

- [Project Management Overview](octoacme-project-management-overview.md) — Goals, roles, lifecycle, artifacts, and communication cadence.
- [Project Initiation Guide](octoacme-project-initiation.md) — Validate new work, align stakeholders, and decide whether to proceed.
- [Project Planning](octoacme-project-planning.md) — Create the backlog, milestones, estimates, dependencies, risks, and Definition of Done.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Manage team rhythm, delivery workflow, quality, metrics, and escalation.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Maintain risks, communicate status, and escalate issues.
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Prepare, deploy, verify, and roll back releases.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learning and track improvement actions.
- [Roles & Personas](octoacme-roles-and-personas.md) — Responsibilities and goals for common OctoAcme project roles.

## Recommended reading order

Start with the [Project Management Overview](octoacme-project-management-overview.md), then review the [Project Initiation Guide](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md) for new work. During delivery, use [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md). Before shipping, follow the [Release & Deployment Guide](octoacme-release-and-deployment.md); afterward, use [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).
