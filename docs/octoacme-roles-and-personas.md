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

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality strategy, test planning, and acceptance validation for features and releases. They collaborate with product, engineering, and stakeholders to define quality standards and ensure acceptance criteria are met before delivery.

### Responsibilities
- Define quality standards and testing approach (unit, integration, E2E)
- Plan and execute manual and automated testing
- Validate acceptance criteria and sign-off on feature readiness
- Identify and document defects; coordinate with developers on fixes
- Recommend test automation improvements and test coverage targets
- Partner with DevOps to execute smoke tests and post-deploy verifications
- Escalate quality blockers that impact release timelines

### Goals
- Ensure features meet definition of done before merging
- Reduce production defects through comprehensive testing
- Accelerate QA cycles via automation and clear criteria

### Key Interactions
- **With Product Managers:** Review acceptance criteria and validate feature usability
- **With Developers:** Triage defects, collaborate on testability improvements
- **With Project Managers:** Escalate quality risks that may impact timeline
- **With DevOps/Infrastructure Engineer:** Coordinate release testing and post-deploy verification

### Decision Authority
- Owns go/no-go quality decisions for feature merges and releases
- Recommends testing approach and automation priorities to engineering leadership

### Typical Communication
- Daily standups and sprint planning
- Test plan reviews and quality metrics reporting
- Release sign-off meetings

---

## Security/Compliance Officer

### Role Summary
Security/Compliance Officers ensure that projects meet security, privacy, and regulatory requirements. They integrate security scanning and compliance checks into development and release processes and advise on risk mitigation strategies.

### Responsibilities
- Define security requirements and compliance standards for projects
- Implement and review security scanning in CI/CD pipelines
- Conduct security reviews and threat assessments
- Manage compliance and regulatory compliance tracking
- Advise on secure coding practices and architecture decisions
- Escalate security vulnerabilities and compliance gaps
- Support incident response and post-incident security reviews

### Goals
- Minimize security vulnerabilities and compliance risks
- Enable secure development without blocking delivery
- Ensure regulatory and policy adherence

### Key Interactions
- **With Developers:** Review code for security risks, provide secure coding guidance
- **With DevOps/Infrastructure Engineer:** Ensure security scanning and controls in pipelines
- **With Project Managers:** Escalate security blockers and compliance timelines
- **With Product Managers:** Incorporate security requirements into product planning
- **With Technical Lead/Architect:** Review architectural security decisions

### Decision Authority
- Owns security sign-off for releases
- Recommends security controls and compliance measures
- Can escalate security incidents to Sponsor/Executive Stakeholder

### Typical Communication
- Security review meetings and threat assessments
- Compliance audit participation
- Incident response coordination
- Weekly security metrics and vulnerability reporting

---

## DevOps/Infrastructure Engineer

### Role Summary
DevOps Engineers design, build, and maintain the deployment infrastructure, CI/CD pipelines, and observability tooling. They enable safe, rapid, and reliable releases to production.

### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Manage deployment environments (staging, production)
- Configure and monitor infrastructure and observability
- Implement security scanning and compliance checks in pipelines
- Document deployment procedures and rollback plans
- Collaborate on capacity planning and performance tuning
- Support incident response and post-incident improvements

### Goals
- Enable fast, safe, and repeatable deployments
- Minimize deployment-related incidents and rollbacks
- Maintain high system reliability and observability

### Key Interactions
- **With Developers:** Provide CI/CD guidance, troubleshoot pipeline issues
- **With QA/Testing Lead:** Coordinate smoke testing and post-deploy verification
- **With Project Managers:** Communicate deployment readiness and risk mitigation
- **With Security/Compliance Officer:** Ensure security scanning and compliance in pipelines
- **With Technical Lead/Architect:** Align infrastructure with system design

### Decision Authority
- Owns deployment strategy and infrastructure architecture
- Recommends deployment safety measures and rollback thresholds
- Can recommend infrastructure improvements based on performance metrics

### Typical Communication
- Release planning and pre-deployment reviews
- Incident response and post-incident retrospectives
- Infrastructure and observability metrics updates
- Capacity planning meetings

---

## Design/UX Lead

### Role Summary
Design/UX Leads define user experience, design standards, and usability requirements. They ensure features are intuitive, accessible, and meet user needs while maintaining design consistency across the product.

### Responsibilities
- Define user experience strategy and design standards
- Create wireframes, prototypes, and design specifications
- Conduct user research and usability testing
- Ensure accessibility and usability compliance
- Review feature designs and provide design guidance
- Advocate for user-centered decision-making
- Document design patterns and guidelines

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce user confusion and support burden
- Maintain design consistency and quality standards

### Key Interactions
- **With Product Managers:** Collaborate on user research and feature prioritization
- **With Developers:** Review implementation against design specifications, iterate on usability
- **With Project Managers:** Communicate design timeline and resource needs
- **With Technical Lead/Architect:** Ensure technical feasibility of design solutions

### Decision Authority
- Owns design approval for features
- Recommends design standards and accessibility requirements
- Can escalate usability concerns that impact user satisfaction

### Typical Communication
- Design review meetings and critique sessions
- Usability testing and user research findings
- Design specification documentation
- Weekly design metrics and feedback

---

## Sponsor/Executive Stakeholder

### Role Summary
Sponsor/Executive Stakeholders provide strategic direction, business alignment, and decision authority for projects. They oversee resource allocation, escalation, and ensure projects deliver business value.

### Responsibilities
- Provide strategic direction and business context for projects
- Approve project charter and resource allocation
- Make high-level trade-off and priority decisions
- Escalate and resolve business-level blockers
- Review project outcomes and measure business impact
- Champion projects and secure stakeholder buy-in
- Communicate project status to broader leadership

### Goals
- Ensure projects deliver business value and align with strategy
- Minimize business-impacting delays and risks
- Maximize ROI and stakeholder satisfaction

### Key Interactions
- **With Product Managers:** Align on business outcomes and priorities
- **With Project Managers:** Receive escalations and make funding/resource decisions
- **With All Roles:** Provide strategic context and decision authority

### Decision Authority
- Owns business-level go/no-go decisions
- Approves resource allocation and timeline trade-offs
- Can override technical or process decisions for business reasons

### Typical Communication
- Monthly executive status reports
- Quarterly business reviews and forecasting
- Ad-hoc escalation and decision requests
- Stakeholder briefings and announcements

---

## Technical Lead/Architect

### Role Summary
Technical Leads and Architects provide technical guidance, design reviews, and risk mitigation for complex projects. They ensure technical decisions align with long-term architecture, scalability, and maintainability goals.

### Responsibilities
- Define technical architecture and design patterns
- Conduct technical design reviews and provide guidance
- Identify technical risks and propose mitigations
- Mentor developers and support knowledge sharing
- Evaluate technology choices and trade-offs
- Ensure code quality and maintainability standards
- Support performance optimization and scalability planning

### Goals
- Deliver scalable, maintainable, and reliable technical solutions
- Reduce technical debt and architectural risks
- Enable team growth through mentorship and knowledge transfer

### Key Interactions
- **With Developers:** Provide technical guidance, code review, and mentorship
- **With Product Managers:** Advise on technical feasibility and impact of requirements
- **With Project Managers:** Escalate technical risks and estimate technical complexity
- **With DevOps/Infrastructure Engineer:** Align infrastructure with system design
- **With Design/UX Lead:** Ensure technical feasibility of design solutions
- **With Security/Compliance Officer:** Review architectural security decisions

### Decision Authority
- Owns technical architecture decisions
- Recommends technical standards and best practices
- Can escalate technical risks to Project Manager and Sponsor

### Typical Communication
- Technical design review meetings
- Architecture decision records (ADRs)
- Technical mentorship and code reviews
- Performance and scalability assessments

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Personas are organized to show clear decision authority and escalation paths across OctoAcme projects.
