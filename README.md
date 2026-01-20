# 🚀 Epic-templates

[![Download Word Template](https://img.shields.io/badge/DOWNLOAD-WORD_TEMPLATE-2B579A?style=for-the-badge&logo=microsoftword&logoColor=white)](https://github.com/EpicKanbanSystem/Epic-templates/raw/main/Epic%20Template%20Auto%20Gen.docx)

### Standardized Epic templates for large-scale scientific software development at ISIS Neutron and Muon Source.

---

## 📖 Project Overview
This repository contains the official **Epic Template** used to capture and define high-level initiatives and software requirements. Originally adapted from the **Scaled Agile Framework (SAFe)**, this template is specifically refined to meet the unique scientific and technical needs of the **ISIS Neutron and Muon Source**.

### 🔗 Part of the Epic Kanban System
This project is designed to work in tandem with our workflow definitions:
* **[Kanban-system-templates](https://github.com/EpicKanbanSystem/Kanban-system-templates)**: Defines the lifecycle and [Kanban States](https://github.com/EpicKanbanSystem/Kanban-system-templates/blob/main/Kanban-States-Definitions.md) through which these Epics progress.

---

## ✨ Key Features
* **Scientific Alignment:** Dedicated sections for scientific impact, methodology, and research context.
* **Agile Integration:** Seamlessly maps to SAFe Portfolio and Program levels.
* **Automated Word Export:** Powered by GitHub Actions and Pandoc. Any change to the Markdown template automatically generates a polished `.docx` file for stakeholder distribution.
* **Consistency:** Ensures all large-scale software projects within the facility follow the same rigorous documentation standard.

---

## 🛠 How to Use
1. **Browse the Template:** View the current [template-without-comments.md](template-without-comments.md) to understand the required fields.
2. **Download for Editing:** Click the **Big Blue Button** at the top of this page to download the latest auto-generated Word version.
3. **Contribute Improvements:** - If you are a team member, update the `.md` file directly to improve the template structure.
   - If you are an external contributor, please submit a **Pull Request**.

---

## ⚙️ Automation Details
This repository uses a **GitHub Action** to keep the Word and Markdown versions in sync:
- **Trigger:** Any push to a `.md` file.
- **Process:** Pandoc converts the Markdown using `Epic template.docx` as a style reference.
- **Output:** The result is committed back to the repo as `Epic Template Auto Gen.docx`.

---

## 👥 Contributors & Contact
* **ISIS Neutron and Muon Source** - *Portfolio Management & Scientific Computing*
* **Maintainers:** [EpicKanbanSystem Team]

---
*Generated with ❤️ by the Epic Kanban System automation suite.*
