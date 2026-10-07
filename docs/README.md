# OctoAcme Project Management Docs

Welcome to OctoAcme's project management knowledge base. This directory contains comprehensive guidance on how we plan, execute, and deliver projects.

## Our Approach

OctoAcme follows a structured, iterative project management methodology based on these core principles:

- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver small, testable increments and gather feedback continuously
- **Clear ownership**: Every project has named roles with clear accountability
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and blameless retrospectives

## Project Lifecycle

1. **Initiation**: Validate business need, align stakeholders, and define success criteria
2. **Planning**: Break work into shippable increments and create a detailed delivery plan
3. **Execution**: Build, test, iterate, and track progress with daily standups
4. **Release**: Deploy to production with confidence and verify success metrics
5. **Close & Improve**: Capture learnings and feed improvements back into processes

## Documentation Guide

Start here based on your role or current project phase:

- **[Project Management Overview](./octoacme-project-management-overview.md)** — Quick introduction to roles, principles, and the project lifecycle
- **[Project Initiation](./octoacme-project-initiation.md)** — Validate ideas and secure stakeholder alignment
- **[Project Planning](./octoacme-project-planning.md)** — Create backlog, timelines, and release plans
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage daily execution, standups, and risk escalation
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Track risks, dependencies, and stakeholder updates
- **[Release & Deployment](./octoacme-release-and-deployment.md)** — Standardize deployments and manage rollbacks
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and drive improvements
- **[Roles and Personas](./octoacme-roles-and-personas.md)** — Understand OctoAcme roles and responsibilities

## Quick Reference

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md)
- **Starting a new project?** Follow the [Initiation](./octoacme-project-initiation.md) and [Planning](./octoacme-project-planning.md) guides
- **In active delivery?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management](./octoacme-risks-and-communication.md)
- **Preparing for release?** Use the [Release & Deployment](./octoacme-release-and-deployment.md) guide
- **Closing a project?** Run through [Retrospectives](./octoacme-retrospective-and-continuous-improvement.md)

## OctoAcme Process Overview

OctoAcme's project management methodology is built around five key phases that enable consistent, repeatable project execution:

### **Initiation Phase**
Define the initial steps to validate and authorize work, align stakeholders, and create a lightweight plan. Every project begins with a Project One-pager that confirms business need, identifies stakeholders, defines success criteria, and establishes key milestones. The decision gate ensures success metrics are clear, stakeholders are aligned, and team availability is confirmed before moving forward.

### **Planning Phase**
Turn an approved initiative into an actionable plan and backlog for delivery. Planning activities include kickoff meetings with stakeholders and delivery teams, creating a prioritized backlog with acceptance criteria, estimating scope, defining Definition of Done, and identifying dependencies. The planning phase produces a release plan and milestone map that guides execution.

### **Execution & Tracking Phase**
Manage day-to-day execution and track progress toward project milestones. OctoAcme's execution approach includes:
- Daily standups (15 min) to focus on progress, blockers, and dependencies
- Weekly delivery sync to show progress and flagged risks
- Project boards with standard workflow columns: Backlog, Ready, In Progress, In Review, QA, Done
- Small PRs (≤400 lines) with automated testing and CI/CD validation
- Quality assurance through unit tests, integration tests, and smoke tests
- Regular metrics tracking and dashboard monitoring

### **Release & Deployment Phase**
Standardize how OctoAcme releases features to production to reduce risk and improve observability. Release types include Patch (hotfixes), Minor (incremental features), and Major (significant functionality or breaking changes). All releases follow pre-release requirements including passing CI/security scans, prepared smoke tests, and documented rollback plans. Post-deployment verification and stakeholder announcements complete the process.

### **Retrospective & Continuous Improvement Phase**
Capture learnings and convert them into actionable improvements. After each sprint, release, or milestone, teams conduct structured retrospectives to discuss what went well and what could be improved. Action items are tracked through the project backlog with clear owners and due dates, enabling continuous measurement of impact and incremental process enhancements.

## How to Use These Docs

- Keep your Project Charter updated in your project repository
- Link to relevant process docs from your project README
- Share docs with stakeholders during kickoffs and planning sessions
- Reference acceptance criteria templates and checklists when planning sprints
- Use this hub as your entry point when onboarding to OctoAcme projects
