# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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

### Interactions with Other Roles
- **With QA/Testing Specialist**: Collaborate on test planning; respond to quality feedback and bug reports
- **With Product Managers**: Clarify acceptance criteria; discuss trade-offs and technical constraints
- **With Project Managers**: Provide effort estimates and status updates; escalate blockers
- **With Technical Architect**: Follow architectural designs and technical decisions; propose alternative approaches

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

### Interactions with Other Roles
- **With Developers**: Define acceptance criteria; discuss feasibility and trade-offs
- **With Project Managers**: Align on priorities and release planning; communicate with sponsors
- **With Sponsor/Executive Stakeholder**: Secure business alignment and budget; present success metrics
- **With Security Lead**: Incorporate security requirements into acceptance criteria

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

### Interactions with Other Roles
- **With Developers & QA**: Track progress; identify and escalate blockers; manage dependency risks
- **With Product Managers**: Align on priorities; coordinate release timelines
- **With Sponsor/Executive Stakeholder**: Report on milestone progress; escalate business-impacting risks
- **With Technical Architect**: Incorporate architectural milestones and dependencies into the plan
- **With Release Manager**: Coordinate deployment schedules and rollback procedures

---

## QA/Testing Specialist

### Role Summary
QA/Testing Specialists validate that features meet acceptance criteria and quality standards. They design test plans, coordinate testing activities, and report on quality metrics to ensure reliable releases.

### Responsibilities
- Design and execute test plans for features and releases
- Validate that acceptance criteria are met before marking work as complete
- Coordinate smoke tests, security scanning, and manual QA
- Identify, document, and track bugs and quality issues
- Report on test coverage and quality metrics
- Participate in release readiness reviews

### Goals
- Ensure high-quality releases with minimal post-production defects
- Provide clear, actionable feedback to development teams
- Support timely release cycles without compromising quality

### Typical Communication
- Test planning sessions with developers and project managers
- Bug reports and quality metrics in weekly syncs
- Release readiness reviews and post-deployment verification reports
- Collaboration with Security Lead on security testing

### Interactions with Other Roles
- **With Developers**: Clarify acceptance criteria; provide bug feedback; collaborate on test design
- **With Project Managers**: Report on test progress; flag quality risks that impact timelines
- **With Security Lead**: Execute security tests and scanning; coordinate security validation
- **With Release Manager**: Validate readiness for deployment; execute post-deploy smoke tests

---

## Sponsor/Executive Stakeholder

### Role Summary
Sponsors/Executive Stakeholders represent business priorities and provide strategic direction. They approve go/no-go decisions at key milestones, advocate for project funding, and serve as escalation points for business-impacting issues.

### Responsibilities
- Approve project initiation and go/no-go decisions at key decision gates
- Provide business context, strategic priorities, and success criteria
- Allocate budget and resources for the project
- Serve as escalation point for business-impacting risks and decisions
- Review milestone status and validate that outcomes align with business goals
- Communicate project status to broader leadership and stakeholders

### Goals
- Ensure projects deliver measurable business value
- Align project execution with strategic priorities
- Manage business risks and escalations effectively
- Maintain stakeholder confidence and transparency

### Typical Communication
- Project initiation reviews and decision gate approvals
- Monthly stakeholder updates and milestone reviews
- Executive escalations for business-impacting risks
- Post-release outcome reviews

### Interactions with Other Roles
- **With Project Managers**: Receive status updates and escalations; make business-impacting decisions
- **With Product Managers**: Align on business goals and success metrics; approve roadmap prioritization
- **With Developers & Technical Architect**: Understand technical trade-offs and feasibility challenges via Project Manager
- **With Release Manager**: Approve release schedules and post-release communications

---

## Security Lead/Officer

### Role Summary
Security Leads ensure that projects meet security and compliance requirements. They participate in risk assessments, gate releases for security compliance, and coordinate incident response when needed.

### Responsibilities
- Define security requirements for projects and features
- Participate in risk assessment and threat modeling
- Review and approve security designs and implementation
- Gate releases for security compliance and scanning
- Coordinate incident response and breach protocols
- Ensure CI/CD pipelines include security scanning and validation
- Advise on security best practices and compliance standards

### Goals
- Prevent security breaches and data loss
- Ensure compliance with organizational and regulatory standards
- Build a culture of security awareness across the team
- Enable fast, secure releases

### Typical Communication
- Security requirement workshops during project planning
- Design and code review participation
- Risk register updates and threat assessments
- CI/CD security scanning and validation gates
- Incident response coordination and blameless retrospectives

### Interactions with Other Roles
- **With Product Managers**: Incorporate security requirements into acceptance criteria
- **With Developers**: Review code and designs for security; provide guidance on secure implementation
- **With QA/Testing Specialist**: Coordinate security testing and scanning; validate compliance
- **With Technical Architect**: Participate in architectural reviews for security implications
- **With Release Manager**: Gate deployments for security compliance; coordinate security announcements

---

## Technical Architect

### Role Summary
Technical Architects design the overall technical solution and integration points for projects. They identify scalability, performance, and dependency risks, and ensure that solutions align with organizational standards and long-term technical strategy.

### Responsibilities
- Design technical solution and architecture for features and projects
- Identify scalability, performance, and maintainability concerns
- Review and approve technical designs and major implementation decisions
- Identify cross-team dependencies and integration risks
- Participate in planning to ensure technical feasibility
- Propose mitigations for technical risks
- Ensure alignment with organizational standards and technology stack

### Goals
- Enable fast, reliable delivery of scalable solutions
- Minimize technical debt and rework
- Reduce cross-team integration risks
- Support long-term technical sustainability

### Typical Communication
- Technical design reviews and architectural workshops
- Design documentation and decision logs
- Planning and risk assessment participation
- Technical risk registers and mitigation discussions
- Code review and guidance on major implementation decisions

### Interactions with Other Roles
- **With Developers**: Guide architectural decisions; review implementations for alignment
- **With Project Managers**: Contribute technical feasibility input to timelines and risk registers
- **With Product Managers**: Discuss technical trade-offs and implications of product decisions
- **With Security Lead**: Participate in security architecture reviews and threat assessments
- **With Technical teams**: Coordinate on cross-team dependencies and integration points

---

## Release Manager/Operations

### Role Summary
Release Managers coordinate deployment schedules, manage rollback procedures, and ensure that releases are deployed safely and reliably. They monitor post-deployment health and communicate release status to support teams and stakeholders.

### Responsibilities
- Coordinate deployment schedules and windows
- Manage pre-deployment checklists and readiness verification
- Deploy to staging and production environments
- Execute rollback procedures if deployment fails or causes critical issues
- Monitor post-deployment health and run post-deploy verifications
- Communicate release status to support teams and stakeholders
- Own incident response and playbook execution during deployment issues
- Track deployment metrics and lessons learned

### Goals
- Deploy releases reliably with minimal downtime or incidents
- Enable fast release cycles without compromising stability
- Maintain clear communication with support and stakeholders
- Continuously improve deployment processes and automation

### Typical Communication
- Pre-release readiness reviews with development and QA teams
- Deployment window notifications to stakeholders
- Real-time incident updates during deployments
- Post-deployment verification reports
- Release notes and deployment metrics in retrospectives

### Interactions with Other Roles
- **With QA/Testing Specialist**: Coordinate on smoke tests and readiness verification
- **With Developers**: Troubleshoot deployment issues; coordinate hotfixes
- **With Project Managers**: Report on deployment progress; escalate business-impacting issues
- **With Security Lead**: Ensure security compliance before and after deployment; coordinate security patches
- **With Sponsor/Executive Stakeholder**: Communicate release status and incident updates

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Interactions with Other Roles" section to understand how personas collaborate and communicate.
