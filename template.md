# Epic Issue Form – Specification (SAFe)

This document describes the **GitHub Epic Issue Form** used by the Epic Kanban System.

> ⚠️ **This is the review and discussion version**
>
> The live, executable form is maintained in:
> `.github/ISSUE_TEMPLATE/epic.yml`

To propose changes:
1. Open a Pull Request modifying this file
2. Discuss changes using GitHub review comments
3. Maintainers will synchronise agreed changes into `epic.yml`

---

## Design Principles

- Minimise friction for early funnel entry
- Encourage benefit-driven thinking
- Align with SAFe Portfolio Epics
- Be usable by non-software scientists
- Avoid YAML exposure to contributors

---

## Epic Overview

**Purpose:**  
Capture large scientific software needs (≥ 0.25 FTY) suitable for Portfolio Kanban.

---

## Fields

### Funnel Entry Date
**Type:** Required  
**Format:** `YYYY-MM-DD`  
**Rationale:** Enables portfolio flow tracking.

---

### Epic Owner
**Type:** Required  
**Rationale:** Single accountable owner for requirements and validation.

---

### Key Stakeholders
**Type:** Optional  
**Rationale:** Identifies affected groups and decision-makers.

---

### Epic Description
**Type:** Required  
**Format:** For / Who / What / Why

```text
For <users or groups>
who <do something>
the <software / tool / service>
is a <short description>
that <provides value>
unlike <current solution>
our solution <does something better>
