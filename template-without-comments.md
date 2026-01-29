---
Title: Epic Template without comments
version: 2.2
status: Active
---
# Name of Epic

> **Note:** The concept of an Epic here is an adaptation of an Epic within the Scale Agile Framework (SAFe).

## Overview

* **Definition:** An Epic refers to a perceived large scientific software need/idea that will advance aspects of ISIS.
* **Threshold:** Consider "large" to mean a need with an initial estimate requiring the effort of at least one person for a quarter of a year or more (≥ 0.25 FTY) to complete all features in scope.
* **Process:** To start an Epic, the minimum required information is a Funnel Entry Date, a title, and an initial Epic Description.
* **Support:** If you are not a member of the scientific software group, please notify your contact within the group or contact Janu (januka.wijesinghe-ekanayaka@stfc.ac.uk) or Anders (anders.markvardsen@stfc.ac.uk) for early feedback.

---

## 1. Epic Metadata

| Field | Description | Input |
| :--- | :--- | :--- |
| **Funnel Entry Date** | Date started | `[YYYY-MM-DD]` |
| **Epic Owner** | The key individual driving the Epic (usually provides requirements/represents users). | `[Name]` |
| **Key Stakeholders** | Relevant stakeholders (scientists, user groups, project managers). | `[Names]` |

---

## 2. Epic Description

*(Suggest initiating the writing in the "For, Who..." format below. If unsure if this is a Business or Enabler Epic, specify why.)*

* **For:** `<users and/or groups of users>`
* **Who:** `<do something, such as a certain type of experiment>`
* **The:** `<scientific software solution/tool/framework/algorithm/service>`
* **Is a:** `<short description of what it is>`
* **That:** `<provides this value>`
* **Unlike:** `<competitor, current solution, or non-existing solution>`
* **Our solution:** `<does something better>`

**Type of Epic:**
* [ ] **Business Epic:** Provides new functionality to external users and ISIS staff.
* [ ] **Enabler Epic:** Enables or improves the ease of creating future Business Epics (e.g., architecture, infrastructure).

**Downside Analysis (Optional):**
* *Is there a significant downside if this problem is not solved?*

---

## 3. Value & Metrics

### Measurable ISIS Benefits
*(Measurable benefits anticipated if the Epic hypothesis is proven true. E.g., "Improve accuracy of data process X by Y%". How does ISIS benefit as an organization?)*

* `[Enter benefits here]`

### Leading Indicators
*(Metrics checked during implementation to track progress. E.g., "Time to run workflow X on hardware Z". Note: Some Epics may strictly rely on MVP completion for feedback.)*

* `[Enter indicators here]`

---

## 4. Scope Definition

| Full Scope (Total Implementation) | MVP Scope (Minimum Viable Product) |
| :--- | :--- |
| **Features in Scope:** | **Features in MVP:** |
| *Full list of features needed to deliver the Epic.* | *Minimum 'experiment' to demonstrate benefits.* |
| * `[Feature 1]` | * `[MVP Feature 1]` |
| * `[Feature 2]` | * `[MVP Feature 2]` |
| * `[Feature 3]` | * `[MVP Feature 3]` |
| | |
| **Out of Scope / Exclusions:** | **Success Criteria:** |
| * `[Clarify exclusions/assumptions]` | * `[How we know the MVP worked]`

---

## 5. Requirements & Constraints

### Nonfunctional Requirements (NFRs)
*(Performance, usability, maintainability, scalability, security, etc.)*

* `[Enter NFRs]`

### Environmental Sustainability
*(CPU/memory usage, energy consumption, hardware needs. Does this impact instrument operations?)*

* `[Enter details]`

### External Commitments
*(E.g., Commissioning date of a new instrument or technique)*

* `[Enter dates/deadlines]`

---

## 6. Forecasted Costs

| Full Implementation (In Scope) | MVP Cost (Experiment) |
| :--- | :--- |
| **Select Estimate Range (FTY):** | **Select Estimate Range (FTY):** |
| [ ] 0.2 - 0.6 FTY | [ ] 0.2 - 0.6 FTY |
| [ ] 1 - 2 FTY | [ ] 1 - 2 FTY |
| [ ] 2.5 - 4 FTY | [ ] 2.5 - 4 FTY |
| [ ] 5 - 8 FTY | [ ] 5 - 8 FTY |
| [ ] 10 - 15 FTY | [ ] 10 - 15 FTY |
| [ ] 20+ FTY | [ ] 20+ FTY |
| | |
| **Detailed Breakdown:** | **Detailed Breakdown:** |
| **Dev Estimate:** `[Value]` | **MVP Dev Estimate:** `[Value]` |
| **Scientist Estimate:** `[Value]` | **Scientist Estimate:** `[Value]` |
| **Skills:** `[List all skills required]` | **Skills:** `[E.g., Mantid, C++, Python]` |

---

## 7. Additional Supporting Data

**Attachments:**
*(Links to resources, architecture diagrams, specs)*

* `[Link 1]`
* `[Link 2]`

---
*Epic template version 2.2 (Jan 2025)*
