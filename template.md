name: Epic (SAFe)
description: Propose a large scientific software Epic (≥ 0.25 FTY)
title: "[Epic]: "
labels:
  - epic
  - funnel
assignees: []

body:
  - type: markdown
    attributes:
      value: |
        ## Epic Overview
        This template is for proposing **large scientific software Epics** aligned with SAFe.
        An Epic typically represents ≥ **0.25 FTY** of effort.

  - type: input
    id: funnel_entry_date
    attributes:
      label: Funnel Entry Date
      description: Date you started filling in this Epic
      placeholder: YYYY-MM-DD
    validations:
      required: true

  - type: input
    id: epic_owner
    attributes:
      label: Epic Owner
      description: Person best positioned to provide requirements and represent users
      placeholder: Name / GitHub handle / email
    validations:
      required: true

  - type: textarea
    id: stakeholders
    attributes:
      label: Key Stakeholders
      description: Scientists, user groups, project or product managers
      placeholder: List stakeholders and their roles
    validations:
      required: false

  - type: textarea
    id: epic_description
    attributes:
      label: Epic Description
      description: |
        Suggested format:
        For / Who / What / Why.
      placeholder: |
        For <users and/or groups of users>
        who <do something>
        the <scientific software / tool / service>
        is a <short description>
        that <provides this value>
        unlike <current solution>
        our solution <does something better>
    validations:
      required: true

  - type: dropdown
    id: epic_type
    attributes:
      label: Type of Epic
      options:
        - Business Epic
        - Enabler Epic
    validations:
      required: true

  - type: textarea
    id: downside
    attributes:
      label: Downside if Not Solved (Optional)
      description: Is there a significant risk or missed opportunity if this Epic is not addressed?
    validations:
      required: false

  - type: textarea
    id: measurable_benefits
    attributes:
      label: Measurable ISIS Benefits
      description: Quantitative or qualitative benefits to ISIS
      placeholder: |
        Examples:
        - Reduced data processing time
        - Improved experiment accuracy
        - Increased scientific throughput
    validations:
      required: true

  - type: textarea
    id: leading_indicators
    attributes:
      label: Leading Indicators
      description: Metrics that indicate progress during implementation
      placeholder: |
        Examples:
        - Runtime of workflow X on dataset Y
        - Error/crash report quality
    validations:
      required: false

  - type: textarea
    id: features_in_scope
    attributes:
      label: Features in Scope
      description: Full list of features required beyond the MVP
    validations:
      required: true

  - type: textarea
    id: out_of_scope
    attributes:
      label: Out of Scope (Optional)
      description: Explicitly excluded functionality or assumptions
    validations:
      required: false

  - type: textarea
    id: mvp_description
    attributes:
      label: MVP Description
      description: The smallest experiment that demonstrates the required benefits
    validations:
      required: true

  - type: textarea
    id: nfrs
    attributes:
      label: Non-Functional Requirements (NFRs)
      description: |
        Performance, usability, maintainability, scalability, logging, security, etc.
    validations:
      required: false

  - type: textarea
    id: sustainability
    attributes:
      label: Environmental Sustainability
      description: |
        Consider CPU, memory, energy usage, hardware requirements, and wider impacts.
    validations:
      required: false

  - type: textarea
    id: external_commitments
    attributes:
      label: External Commitments
      description: Commissioning dates, instrument timelines, external dependencies
    validations:
      required: false

  - type: dropdown
    id: full_cost_range
    attributes:
      label: Estimated Full Implementation Cost (FTY)
      options:
        - 0.2–0.6 FTY
        - 1–2 FTY
        - 2.5–4 FTY
        - 5–8 FTY
        - 10–15 FTY
        - 20+ FTY
    validations:
      required: true

  - type: textarea
    id: full_cost_details
    attributes:
      label: Cost Breakdown & Skills Required
      description: Development estimate, scientist estimate (if ≥ 0.1 FTY), and required skills
    validations:
      required: false

  - type: dropdown
    id: mvp_cost_range
    attributes:
      label: Estimated MVP Cost (FTY)
      options:
        - 0.2–0.6 FTY
        - 1–2 FTY
        - 2.5–4 FTY
        - 5–8 FTY
    validations:
      required: true

  - type: textarea
    id: mvp_skills
    attributes:
      label: Skills Required for MVP
      description: |
        e.g. Mantid, GUI, C++, GPU, Python, McStas
    validations:
      required: false

  - type: textarea
    id: attachments
    attributes:
      label: Additional Supporting Data
      description: Links to relevant documentation, diagrams, or specifications
    validations:
      required: false
