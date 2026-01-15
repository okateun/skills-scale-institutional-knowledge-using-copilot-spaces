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

---

## Release Manager

### Role Summary
Release Managers coordinate the end-to-end release process from planning through deployment and post-release validation. They ensure releases are well-coordinated, risks are minimized, and stakeholders are informed throughout the release lifecycle.

### Responsibilities
- Plan and schedule release windows across environments
- Coordinate release activities among development, QA, and operations teams
- Maintain release calendar and ensure alignment with business needs
- Oversee release checklist execution and gate reviews
- Manage release communications to stakeholders and support teams
- Track release metrics and identify process improvements
- Coordinate rollback procedures when issues arise
- Ensure release documentation is complete and accurate

### Goals
- Deliver releases on schedule with minimal disruption
- Maintain high release success rate and reduce incidents
- Provide clear visibility into release status and risks
- Continuously improve release efficiency and automation

### Typical Communication
- Release planning meetings with Product and Engineering leads
- Pre-release readiness reviews and go/no-go decisions
- Post-deployment status updates and release notes
- Incident coordination during release issues

### Interactions with Other Roles
- **Project Managers**: Align release timelines with project milestones and dependencies
- **Developers**: Coordinate code freeze periods and deployment readiness
- **QA Lead**: Confirm test completion and quality gates before release
- **Product Managers**: Validate feature readiness and communication plans
- **Change Control Coordinator**: Ensure proper change approval and documentation

---

## QA Lead

### Role Summary
QA Leads define and execute the quality assurance strategy for projects, ensuring features meet acceptance criteria and quality standards. They coordinate testing activities, manage test environments, and advocate for quality throughout the development lifecycle.

### Responsibilities
- Define test strategy and coverage requirements for projects
- Lead test planning and coordinate testing activities
- Review acceptance criteria for testability and completeness
- Manage test environments and test data
- Execute and oversee manual and automated testing
- Track and triage defects with development teams
- Report on quality metrics and test progress
- Identify quality risks and recommend mitigations

### Goals
- Ensure features meet quality standards before release
- Maximize test coverage and automation efficiency
- Reduce escaped defects and production incidents
- Enable fast, confident deployments

### Typical Communication
- Test status updates in standups and delivery syncs
- Quality gate reviews before releases
- Defect triage meetings with developers
- Test plan reviews with Product and Project Managers

### Interactions with Other Roles
- **Developers**: Collaborate on testability, review test cases, triage defects
- **Project Managers**: Report testing progress and quality risks
- **Product Managers**: Validate acceptance criteria and priority of defects
- **Release Manager**: Confirm quality gates and testing completion for releases
- **Change Control Coordinator**: Validate testing for change requests

---

## Change Control Coordinator

### Role Summary
Change Control Coordinators manage the formal change management process to ensure modifications to systems, processes, or documentation are properly reviewed, approved, and tracked. They maintain accountability and reduce risks associated with changes.

### Responsibilities
- Facilitate change review board meetings and approvals
- Maintain change request documentation and tracking
- Ensure changes follow established governance processes
- Assess change impact and coordinate risk evaluation
- Track change implementation and validation
- Maintain audit trail for compliance and reporting
- Coordinate emergency change procedures when needed
- Report on change metrics and process compliance

### Goals
- Minimize risk from unauthorized or poorly planned changes
- Ensure regulatory and compliance requirements are met
- Maintain clear audit trail for all changes
- Enable efficient change approval without blocking delivery

### Typical Communication
- Change advisory board meetings and approvals
- Change impact assessments with technical teams
- Compliance reports to stakeholders and auditors
- Emergency change coordination during incidents

### Interactions with Other Roles
- **Project Managers**: Review project-related changes and dependencies
- **Developers**: Gather technical details for change requests
- **Release Manager**: Coordinate release changes and deployment windows
- **QA Lead**: Ensure adequate testing for changes
- **Data Steward**: Review data-related changes for governance compliance

---

## Data Steward

### Role Summary
Data Stewards ensure data is managed according to governance policies, quality standards, and regulatory requirements. They act as custodians of data assets, maintaining data integrity, security, and accessibility across the organization.

### Responsibilities
- Define and enforce data governance policies and standards
- Monitor data quality and coordinate remediation efforts
- Manage data access controls and permissions
- Ensure compliance with data privacy and security regulations
- Document data lineage, definitions, and metadata
- Coordinate data-related change requests and migrations
- Provide guidance on data usage and best practices
- Track data governance metrics and audit compliance

### Goals
- Maintain high data quality and integrity
- Ensure data security and regulatory compliance
- Enable trusted, accessible data for business decisions
- Minimize data-related risks and incidents

### Typical Communication
- Data governance committee meetings
- Data quality reviews and remediation planning
- Compliance audits and reporting
- Data access request reviews and approvals

### Interactions with Other Roles
- **Developers**: Review data model changes and data handling practices
- **Product Managers**: Advise on data requirements and constraints
- **Change Control Coordinator**: Review data-related change requests
- **Project Managers**: Identify data governance requirements in projects
- **QA Lead**: Define data quality validation and test data requirements

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

