# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Assign named owners for each responsibility on every project. On smaller teams, one person may cover multiple roles, but accountability and decision authority should remain explicit. Specialist roles may be involved only when project needs or risks warrant them.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

### Interactions and Handoffs
- Work with the Engineering Lead on technical approach, estimates, reviews, and escalation of technical risks.
- Clarify requirements and acceptance criteria with the Product Manager; coordinate milestones and blockers with the Project Manager (PM).
- Partner with Design/UX on feasible, accessible implementation and with QA/Testing on testability, defect triage, and fixes.
- Provide implementation and operational details to the Release Owner for readiness, deployment, and rollback planning.

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Interactions and Handoffs
- Align outcomes, priorities, and major trade-offs with the Project Sponsor and stakeholders.
- Partner with Design/UX to validate user needs and with the Engineering Lead and Developers to assess feasibility and delivery options.
- Coordinate scope, dependencies, and decision records with the PM; work with QA/Testing to ensure acceptance criteria are verifiable.
- Agree release scope and customer-facing outcomes with the Release Owner and Operations/Support Representative.

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

### Interactions and Handoffs
- Maintain the integrated plan and escalation path with the Project Sponsor, Product Manager, and delivery leads.
- Track technical, security, and operational dependencies with their accountable owners, and ensure decisions and mitigations are recorded.
- Coordinate readiness checkpoints with the Release Owner, QA/Testing, and Operations/Support; communicate status, risks, and decisions to stakeholders.
- Facilitate retrospectives and track agreed improvement actions with named owners.

---

## Project Sponsor / Executive Sponsor

### Role Summary
The Project Sponsor champions the business case, provides strategic direction and organizational support, and makes or secures decisions that exceed the project team's authority. Involve the sponsor during initiation, at decision gates, and when business-impacting issues require escalation.

### Responsibilities and Decision Authority
- Confirm the initiative's alignment with organizational goals and expected benefits.
- Help secure funding, capacity, and cross-team commitment.
- Resolve escalated priority, scope, or resource conflicts and approve major changes within governance.
- Review progress and risks at agreed checkpoints; confirm continuation or escalation when outcomes are at risk.

### Goals
- Achieve the intended business outcomes and benefits.
- Ensure the project has clear organizational backing and timely decisions.

### Typical Communication
- Decision-gate and milestone reviews with the PM and Product Manager.
- Escalation briefs covering impact, options, recommendation, and decision needed.

### Interactions and Handoffs
- Partners with the Product Manager to align strategic outcomes and priority, while the Product Manager owns product backlog ordering.
- Partners with the PM on governance, resources, escalations, and stakeholder alignment; the PM maintains delivery coordination and status.
- Receives technical options and risk assessments from the Engineering Lead and specialist owners before making business-level decisions.
- Communicates sponsorship decisions and organizational changes to relevant stakeholders.

---

## Engineering Lead / Technical Lead

### Role Summary
The Engineering Lead guides the technical direction and engineering practices for the project. This role is involved in planning and throughout delivery, particularly where architecture, integrations, reliability, or technical risk require coordination.

### Responsibilities
- Lead technical design and document significant decisions and trade-offs.
- Coordinate engineering estimates, implementation sequencing, and technical dependencies.
- Support code quality, maintainability, testing, and engineering review practices.
- Identify technical risks early and propose mitigations or alternatives.

### Goals
- Deliver a secure, reliable, maintainable solution that meets product needs.
- Make technical decisions and dependencies visible in time to inform plans.

### Typical Communication
- Design reviews and technical decision records.
- Estimates, dependency updates, and risk discussions with the delivery team.

### Interactions and Handoffs
- Works with Developers on design, implementation, review, and technical problem-solving; does not replace individual contributors' ownership of their work.
- Advises the Product Manager on feasibility and trade-offs, and the PM on estimates, milestones, dependencies, and blockers.
- Partners with QA/Testing on test strategy and with Security/Privacy on safeguards and risk remediation.
- Supplies technical readiness, deployment, observability, and rollback information to the Release Owner and Operations/Support Representative.

---

## Designer / UX Researcher

### Role Summary
The Designer / UX Researcher represents user needs through research, interaction and visual design, and usability evaluation. Involve this role when user workflows, accessibility, or experience design materially affect the solution.

### Responsibilities
- Plan or conduct appropriate user research and synthesize findings.
- Create and validate user flows, interaction designs, and design specifications.
- Identify usability and accessibility considerations and help define experience acceptance criteria.
- Review implemented experiences and communicate design changes or gaps.

### Goals
- Ensure solutions address validated user needs and are understandable and usable.
- Surface experience risks before they become costly rework.

### Typical Communication
- Research summaries, design artifacts, and design reviews.
- Collaboration with product and engineering during refinement and implementation.

### Interactions and Handoffs
- Partners with the Product Manager to connect user evidence to problem statements, priorities, and outcomes.
- Works with Developers and the Engineering Lead to assess feasibility and clarify design intent; hands off specifications and assets before implementation.
- Collaborates with QA/Testing on usability and accessibility checks and with Operations/Support on customer feedback after launch.
- Shares research findings with the PM and stakeholders when they affect scope, risks, or decisions.

---

## Release Manager / Release Owner

### Role Summary
The Release Owner coordinates release readiness and the execution or oversight of a release. This role is assigned for planned deployments and may be combined with an engineering or operations role on smaller teams, provided the owner is explicit.

### Responsibilities
- Coordinate the release scope, readiness checklist, timing, and go/no-go inputs.
- Confirm acceptance, CI and security checks, release notes, deployment steps, and rollback or mitigation plans are accounted for.
- Coordinate deployment communications and post-deployment verification.
- Capture release outcomes and unresolved follow-up actions.

### Goals
- Deliver changes safely and predictably with clear ownership and communication.
- Detect release issues promptly and support recovery.

### Typical Communication
- Release readiness reviews and deployment coordination.
- Release notes, launch announcements, and post-deployment status updates.

### Interactions and Handoffs
- Coordinates scope and stakeholder timing with the Product Manager and PM; the PM maintains the overall project plan and the Product Manager confirms product priorities.
- Collects technical deployment and rollback information from the Engineering Lead and Developers.
- Confirms test results and outstanding defects with QA/Testing and security clearance with Security/Privacy when applicable.
- Coordinates support readiness and incident communications with Operations/Support; hands over monitoring and known issues after deployment.

---

## Operations / Support Representative

### Role Summary
The Operations / Support Representative brings service operations and customer-support needs into planning and release, and helps monitor customer impact after launch. Involve this role when changes affect production operations, support workflows, service levels, or customer communications.

### Responsibilities
- Identify operational requirements, monitoring needs, runbook updates, and support impacts.
- Prepare support teams with release information, known issues, escalation routes, and customer guidance.
- Monitor operational signals and support feedback after launch; route incidents through the established response process.
- Share recurring issues and customer insights to inform improvements.

### Goals
- Maintain service reliability and support readiness through change.
- Reduce time to detect, communicate, and resolve customer-impacting issues.

### Typical Communication
- Operational readiness reviews, runbooks, and incident channels.
- Support briefings and post-release feedback with product and delivery teams.

### Interactions and Handoffs
- Partners with the Release Owner on launch readiness, monitoring, communications, and handoff to steady-state operations.
- Works with the Engineering Lead and Developers on observability, operational requirements, and remediation; shares customer-impact evidence with the Product Manager.
- Coordinates incident and stakeholder updates with the PM and follows the incident escalation path.
- Provides QA/Testing with operational scenarios and shares post-launch findings with Design/UX and the broader team.

---

## Security / Privacy Representative

### Role Summary
The Security / Privacy Representative advises on security, privacy, and applicable compliance requirements. Involve this specialist when data sensitivity, system exposure, regulatory obligations, or risk assessments warrant it; define the required review early enough to inform design and delivery.

### Responsibilities
- Identify relevant security, privacy, and compliance requirements and review points.
- Advise on threat, privacy, and risk assessments and recommend safeguards.
- Review evidence or test results for agreed controls and track unresolved findings to an accountable owner.
- Escalate material risks through the organization's security or privacy incident and governance paths.

### Goals
- Address security and privacy risks proportionately and before release.
- Make control requirements, residual risks, and approvals explicit.

### Typical Communication
- Risk reviews, design consultations, and documented findings.
- Time-sensitive escalation through designated security or privacy channels.

### Interactions and Handoffs
- Works with the Engineering Lead and Developers to incorporate safeguards into architecture and implementation, and with QA/Testing to validate applicable controls.
- Advises the Product Manager on user and product implications and the PM on risk tracking, dependencies, and review milestones.
- Provides release conditions or unresolved risk information to the Release Owner; communicates material concerns to the Project Sponsor through agreed governance.
- Coordinates with Operations/Support on security or privacy incident readiness and escalation, without replacing the designated incident-response owner.

---

## QA / Testing

### Role Summary
QA/Testing validates that delivered work meets acceptance criteria and quality expectations. Testing may be performed by dedicated QA specialists, Developers, or a combination, but the project's validation ownership and coverage should be clear.

### Responsibilities
- Define and execute appropriate unit, integration, end-to-end, and manual validation.
- Confirm acceptance criteria are testable and record results, defects, and risks.
- Coordinate defect triage and retesting with Developers and the Engineering Lead.
- Provide an evidence-based quality and readiness assessment to the Release Owner.

### Interactions and Handoffs
- Clarifies acceptance criteria and priority with the Product Manager and coordinates test timing with the PM.
- Works with Developers and the Engineering Lead on testability, defects, and technical risks; consults Design/UX on usability and accessibility validation.
- Confirms security or privacy control testing with the Security/Privacy Representative when applicable.
- Hands test outcomes, open defects, and residual risks to the Release Owner for release decisions.

---

## Stakeholders

### Role Summary
Stakeholders provide domain knowledge, feedback, constraints, or approvals relevant to project outcomes. The PM and Product Manager identify which stakeholders need to be involved and when.

### Responsibilities
- Provide timely input on needs, constraints, dependencies, and proposed outcomes.
- Review deliverables or decisions when their expertise or authority is required.
- Communicate impacts within their areas and raise concerns through agreed channels.

### Interactions and Handoffs
- Work with the Product Manager on user, business, and priority input and with the PM on coordination, status, and decision timing.
- Route approval or resource decisions to the appropriate authority, such as the Project Sponsor, rather than assuming every stakeholder has approval authority.
- Provide feedback to the delivery team through the Product Manager or agreed review process.

---

## Role Assignment Across the Lifecycle

- **Initiation:** The Product Manager frames the problem and outcomes; the PM coordinates the one-pager and stakeholders; the Project Sponsor confirms strategic backing. Engineering, Design/UX, Operations/Support, and Security/Privacy contribute early when relevant.
- **Planning:** The Product Manager prioritizes outcomes and acceptance criteria; the PM maintains milestones, dependencies, and risks; the Engineering Lead and specialists provide estimates, design input, and readiness requirements.
- **Execution:** Developers deliver the work with guidance from the Engineering Lead; Design/UX, QA/Testing, and Security/Privacy validate their areas; the PM coordinates progress and escalations.
- **Release:** The Release Owner coordinates readiness and deployment; QA/Testing provides validation evidence; Engineering supplies deployment and rollback details; Operations/Support prepares for customer impact; Product and PM coordinate scope and communications.
- **Retrospective and follow-up:** The PM facilitates learning and tracks actions; the Product Manager reviews outcome signals; delivery and specialist role owners contribute evidence and take ownership of relevant improvements.

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
