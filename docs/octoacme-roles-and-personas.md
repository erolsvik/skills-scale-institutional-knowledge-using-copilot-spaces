# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Personas

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

## Extended Personas

## Engineering Lead

### Role Summary
Engineering Leads provide technical direction and stewardship for a project or team. They make architectural decisions, ensure code quality, and mentor developers to maintain high standards.

### Responsibilities
- Define technical architecture and design patterns
- Make or guide critical technical decisions
- Establish code quality standards and best practices
- Mentor and support developers on technical growth
- Identify and escalate technical risks and dependencies
- Participate in design reviews and code reviews

### Goals
- Build scalable, maintainable systems
- Reduce technical debt and improve code quality
- Develop the technical skills of the team
- Ensure technical decisions align with product goals

### How They Interact with Existing Roles
- **Works with Product Managers/Product Leads** to translate business requirements into technical architecture and feasibility assessments
- **Collaborates with Developers** to guide implementation, answer design questions, and conduct code reviews
- **Coordinates with Project Managers** on technical milestones and risk escalation
- **Partners with QA/Testing** to define testability requirements and acceptance criteria from a technical perspective

### Typical Communication
- Technical design documents and RFCs (Request for Comments)
- Architecture reviews and design discussions
- Code review comments and technical guidance
- Escalation of technical blockers and risks

---

## Design Lead

### Role Summary
Design Leads own the user experience, visual design, and design system stewardship for a project. They ensure consistency, accessibility, and usability across all user-facing components.

### Responsibilities
- Design user experiences and user interfaces that meet accessibility standards
- Create and maintain design system and component library
- Conduct user research and incorporate feedback into designs
- Review design work and provide direction
- Ensure consistency across the product and brand alignment
- Advocate for accessibility (WCAG compliance, keyboard navigation, screen reader support)

### Goals
- Deliver intuitive, delightful user experiences
- Reduce support load through clear UX and helpful documentation
- Maintain a cohesive product design system
- Ensure accessibility for all users

### How They Interact with Existing Roles
- **Collaborates with Product Managers** to understand user needs, customer pain points, and business goals
- **Hands off designs to Developers** with clear specs, assets, and design system references
- **Partners with Developers** to clarify implementation questions and ensure pixel-perfect fidelity
- **Works with QA/Testing** to define acceptance criteria related to design and usability
- **Coordinates with Engineering Lead** on technical feasibility of design patterns

### Typical Communication
- Design mockups, prototypes, and component specs
- Design critique sessions and design reviews
- User research findings and insights
- Accessibility audit reports and recommendations

---

## Release Manager

### Role Summary
Release Managers coordinate the planning, scheduling, and execution of software releases. They ensure smooth deployments, maintain release documentation, and manage rollback procedures to minimize risk and downtime.

### Responsibilities
- Plan and schedule release windows with minimal business impact
- Coordinate with engineering and operations on deployment logistics
- Draft and maintain release notes and migration guides
- Ensure pre-release checklist is completed (tests, security scans, rollback plan)
- Coordinate deployment execution and post-deploy verification
- Manage rollback procedures if deployment issues occur
- Communicate release status and timing to stakeholders and support teams

### Goals
- Execute deployments with zero or minimal downtime
- Reduce risk and uncertainty in production releases
- Maintain clear, timely communication with all teams and customers
- Enable rapid rollback if critical issues occur

### How They Interact with Existing Roles
- **Works with Project Managers** to plan release schedules and identify dependencies
- **Coordinates with Developers and Engineering Lead** on deployment readiness and risk assessment
- **Partners with DevOps/Platform Engineers** to execute the deployment and provide infrastructure support
- **Communicates with Support and On-call Liaison** to brief them on changes and prepare for incidents
- **Aligns with Product Managers** on messaging and timing for stakeholder communication

### Typical Communication
- Release schedules and deployment calendars
- Release notes and change logs
- Pre-release checklists and verification procedures
- Post-deployment status reports and incident summaries

---

## Security Champion

### Role Summary
Security Champions surface security risks, validate threat models, and triage security findings. They serve as the security-focused advocate within the project and ensure security best practices are followed.

### Responsibilities
- Identify potential security risks in requirements and design
- Validate threat models and security assumptions
- Review security-related code changes and configurations
- Triage and prioritize security findings from scanning tools
- Advise on security trade-offs between features and security controls
- Escalate critical security issues to the Security team
- Promote security awareness and best practices within the team

### Goals
- Reduce security vulnerabilities and incidents
- Build security into the product from the start (shift-left)
- Maintain compliance with security policies and standards
- Enable the team to make informed security decisions

### How They Interact with Existing Roles
- **Liaisons with the Security team** to report findings, get guidance, and escalate critical issues
- **Works with Developers and Engineering Lead** to recommend secure design patterns and review implementations
- **Advises Product Managers** on security implications of feature requests
- **Supports Release Manager** by ensuring security scanning passes before deployment
- **Coordinates with DevOps/Platform Engineers** on secure infrastructure configuration

### Typical Communication
- Security threat assessments and risk analyses
- Code review comments on security concerns
- Security scanning reports and remediation plans
- Security incident communications and post-mortems

---

## DevOps / Platform Engineer

### Role Summary
DevOps and Platform Engineers design, build, and maintain the infrastructure, CI/CD pipelines, and observability systems that enable the team to deploy and run services reliably.

### Responsibilities
- Design and maintain CI/CD pipelines for automated testing and deployment
- Manage infrastructure and environments (dev, staging, production)
- Set up logging, monitoring, and alerting for system health
- Ensure infrastructure security and compliance
- Troubleshoot production incidents and infrastructure issues
- Optimize performance, reliability, and cost of infrastructure
- Document runbooks and procedures for common operational tasks

### Goals
- Enable developers to deploy safely and frequently
- Maintain high availability and performance of services
- Reduce deployment risk and mean time to recovery (MTTR)
- Provide visibility into system health and behavior

### How They Interact with Existing Roles
- **Partners with Developers** to set up builds, deployments, and local development environments
- **Works with Engineering Lead** to design scalable, reliable infrastructure
- **Collaborates with Release Manager** to execute deployments and verify post-deploy health
- **Supports On-call Liaison** by providing runbooks, dashboards, and troubleshooting tools
- **Advises Security Champion** on infrastructure security configuration

### Typical Communication
- CI/CD configuration and deployment procedures
- Infrastructure diagrams and runbooks
- Monitoring dashboards and alerting policies
- Incident post-mortems and reliability retrospectives

---

## Data / Analytics Owner

### Role Summary
Data and Analytics Owners define success metrics, ensure data quality, and build dashboards and reports that enable the team and leadership to measure impact and make data-driven decisions.

### Responsibilities
- Define success metrics aligned with business and product goals
- Design event instrumentation and data collection strategies
- Ensure data quality, accuracy, and completeness
- Build dashboards and reports for real-time visibility
- Analyze trends and patterns to identify opportunities and issues
- Provide insights and recommendations to product and business teams
- Document data definitions and metric calculations for clarity

### Goals
- Enable data-driven decision making at all levels
- Provide clear, actionable insights into product performance
- Reduce ambiguity around what success looks like
- Build trust in metrics through data quality and transparency

### How They Interact with Existing Roles
- **Collaborates with Product Managers** to ensure success metrics are clearly defined and measurable
- **Works with Developers and Engineering Lead** to implement event tracking and instrumentation
- **Provides dashboards to the On-call Liaison** for monitoring system health and customer impact
- **Supports Release Manager** by providing pre- and post-release metrics and impact analysis
- **Advises Project Manager** on KPIs and trend indicators for status reporting

### Typical Communication
- Success metric definitions and KPI dashboards
- Data quality reports and validation findings
- Trend analyses and business insights
- Instrumentation specifications and event definitions

---

## Support / On-call Liaison

### Role Summary
Support and On-call Liaisons serve as the first responder to production incidents and customer issues. They bridge engineering and customer support, communicate status, and escalate as needed to unblock resolution.

### Responsibilities
- Respond to production incidents and page on-call engineering
- Triage issues and gather information for the engineering team
- Communicate incident status and updates to affected customers and stakeholders
- Coordinate incident response and maintain incident timeline
- Escalate critical issues quickly to decision makers
- Feed incident learnings into retrospectives and process improvements
- Document runbooks and troubleshooting procedures for common issues

### Goals
- Minimize incident duration and customer impact
- Provide clear, timely communication during incidents
- Identify systemic issues and drive prevention
- Support the team in resolving issues quickly

### How They Interact with Existing Roles
- **Coordinates with Developers and Engineering Lead** to triage, investigate, and resolve incidents
- **Works with Project Manager** to communicate impact and resolution timeline to leadership
- **Partners with Release Manager** to assess whether a rollback is needed
- **Supports DevOps/Platform Engineers** with infrastructure troubleshooting
- **Communicates with Customer Support** on customer-facing messaging and workarounds
- **Provides feedback to Product Managers** on frequent issues and reliability concerns

### Typical Communication
- Incident alerts and escalation notifications
- Incident status updates and post-incident reports
- Runbooks and troubleshooting guides
- Reliability metrics and incident trends

---

## Business Analyst

### Role Summary
Business Analysts work to clarify requirements, define acceptance criteria, and ensure that solutions meet business needs. They create process flows, document edge cases, and help bridge the gap between business stakeholders and the delivery team.

### Responsibilities
- Clarify business requirements and edge cases with stakeholders
- Work with Product Managers to refine and document acceptance criteria
- Create process flows and user journey maps
- Identify and document assumptions and dependencies
- Support the delivery team in answering requirement questions
- Validate that delivered solutions meet business expectations
- Document procedures and training materials for new features

### Goals
- Reduce rework and misalignment between business needs and delivery
- Ensure solutions are fit-for-purpose and meet all edge cases
- Accelerate onboarding and adoption of new features
- Build shared understanding across business and technical teams

### How They Interact with Existing Roles
- **Works closely with Product Managers and Project Managers** to refine backlog and define requirements
- **Supports Developers and Engineering Lead** by answering requirement questions and clarifying edge cases
- **Collaborates with Design Lead** on user processes and user journeys
- **Provides information to QA/Testing** on acceptance criteria and edge cases to test
- **Assists Release Manager** with documentation and communication about changes

### Typical Communication
- Requirement documents and user stories
- Process flow diagrams and journey maps
- Acceptance criteria and edge case documentation
- Training materials and procedure guides

---

## Change Manager (for major initiatives)

### Role Summary
Change Managers assess the organizational and operational impact of major changes (e.g., large feature releases, platform migrations, organizational changes). They develop communication and change management plans to ensure smooth adoption and minimal disruption.

### Responsibilities
- Assess organizational and operational impact of proposed changes
- Identify stakeholder groups and their concerns
- Develop change communication and change management plans
- Coordinate training and documentation for end users
- Plan rollout phasing and timing to minimize disruption
- Monitor adoption and gather feedback post-launch
- Identify and mitigate resistance and adoption barriers

### Goals
- Ensure smooth adoption of new features and processes
- Minimize disruption to business operations
- Build stakeholder confidence and buy-in
- Enable end users to be productive quickly with changes

### How They Interact with Existing Roles
- **Collaborates with Product Managers and Project Managers** to understand scope and timeline
- **Works with Release Manager** on rollout coordination and timing
- **Supports Design Lead and Business Analyst** on user training and documentation
- **Communicates with Support and On-call Liaison** to prepare support teams for new features
- **Engages with Stakeholders and Leadership** on communication and adoption strategies

### Typical Communication
- Change impact assessments and stakeholder analyses
- Change management and communication plans
- Training materials and readiness assessments
- Adoption metrics and feedback summaries

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Select the personas relevant to your project scope; smaller projects may not require all extended personas.
- Ensure clear handoffs and ownership between personas to avoid gaps or overlaps.
