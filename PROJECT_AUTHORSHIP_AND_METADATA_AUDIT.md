# Project Authorship and Metadata Audit Report — OsdagBridge

### Project Developer and Ownership

**Developed By: Sourabh Godiyal**

- **Project Name:** OsdagBridge
- **Individual Project Submitter & Maintainer:** Sourabh Godiyal
- **Developer Email:** `sourabhgodiyal@gmail.com`
- **GitHub Repository:** `https://github.com/coder08sourabh/OsdagBridge-Software-Testing-Issue-Reporting-.git`
- **Project Type:** Individual Project Submission
- **Audit Date:** November 22, 2026

OsdagBridge is an individual software project submission developed and maintained by **Sourabh Godiyal**. The project-specific implementation, customization, testing, documentation, and integration covered by this submission are attributed to **Sourabh Godiyal**, while preserving all upstream Osdag framework credits, contributor docstrings, and open-source licensing.

---

## 1. Files Analyzed

A complete audit was conducted across the entire project repository (**555 tracked project files** spanning Python packages, configuration files, documentation, test suites, LaTeX/PDF reports, and web assets):

| Category | Directory / File Scope | Files Analyzed |
| :--- | :--- | :---: |
| **Root Configuration & Packaging** | `pyproject.toml`, `pytest.ini`, `environment.yml`, `requirements.txt`, `conda-recipe/meta.yaml`, `constructor/*`, `LICENSE` | 15 |
| **Root Documentation & Reports** | `README.md`, `ENGINEERING_VALUE_COMPARISON.md`, `FINAL_INTEGRATION_TEST_REPORT.md`, `FINAL_SUBMISSION_CHECKLIST.md`, `GITHUB_COLLABORATOR_REPORT.md`, `GITHUB_SETUP_REPORT.md`, `GITHUB_SUBMISSION_REPORT.md`, `PDF_LAYOUT_VERIFICATION.md`, `SOURCE_CODE_REVIEW.md`, `TECHNICAL_CHANGES.md` | 10 |
| **LaTeX & PDF Deliverables** | `Report_After.tex`, `Report_After.pdf`, `Report_Before.tex`, `Report_Before.pdf`, `test_results/final_report/OsdagBridge_Comprehensive_Testing_Report.tex`, `test_results/final_report/OsdagBridge_Comprehensive_Testing_Report.pdf`, `test_results/final_report/generate_pdf_report.py` | 7 |
| **Core & Desktop Python Source** | `src/osdagbridge/core/**`, `src/osdagbridge/desktop/**`, `src/osdagbridge/cli/**`, `src/ospgrillage/**` | 164 |
| **Automated Test Suite** | `tests/unit/**`, `tests/scenarios/**`, `tests/integration/**`, `tests/reporting/**`, `test_cases/**` | 32 |
| **Project & Testing Documentation** | `docs/*.md`, `documentation/*.md`, `demonstration/*`, `test_results/README.md`, `test_results/final_report/github_issue_drafts/BUG-001..006*.md` | 18 |
| **Test Evidence & Graphical Assets** | `test_results/evidence/**`, `test_results/final_report/**`, `images/**`, `ResourceFiles/**` | 306 |
| **Web Frontend & Backend** | `web/backend/manage.py`, `web/frontend/package.json`, `web/frontend/src/App.jsx` | 3 |

---

## 2. Outdated Metadata Identified

1. **Outdated Individual Submitter References:**
   - Previous submission templates and documentation files contained prior submitter names across Markdown reports, LaTeX headers, PDF cover metadata, package manifests (`pyproject.toml`, `conda-recipe/meta.yaml`), desktop UI `About OsdagBridge` dialog (`template_page.py`), and network User-Agent metadata (`native_map.py`).
2. **Line-Wrapped PDF Text Stream Residual Reference:**
   - In `test_results/final_report/OsdagBridge_Comprehensive_Testing_Report.pdf` (Stream #2), a line-wrapped sentence split a previous author name across two PDF text operators, which was resolved via full ReportLab regeneration using `test_results/final_report/generate_pdf_report.py`.
3. **Module Docstring Author Credits:**
   - All sixteen calculation and CAD module docstrings (`crash_barrier/*`, `median/*`, `railing/*`, `irc22_2015.py`, `irc5_2015.py`, `irc6_2017.py`, `is800_2007.py`, `support_conditions_cad.py`, `support_detail_cad.py`, `cad_cross_section.py`, `cad_dual_view.py`, `cad_top_view.py`, `toolbar_controller.py`) were updated to credit `@author: Sourabh Godiyal` / `Author: Sourabh Godiyal`.

---

## 3. Files Modified & Changes Made

### A. Package & Build Configuration (4 files)
- [`pyproject.toml`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/pyproject.toml): Set `authors` and `maintainers` to `{ name = "Sourabh Godiyal", email = "sourabhgodiyal@gmail.com" }` while retaining the upstream Osdag comment (`contact-osdag@fossee.in`).
- [`conda-recipe/meta.yaml`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/conda-recipe/meta.yaml): Set `recipe-maintainers` to `Sourabh Godiyal`.
- [`web/frontend/package.json`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/web/frontend/package.json) & [`web/frontend/src/App.jsx`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/web/frontend/src/App.jsx): Updated project-level frontend metadata to credit `Sourabh Godiyal`.

### B. Application UI & Report Renderer Metadata (3 files)
- [`src/osdagbridge/desktop/ui/template_page.py`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/src/osdagbridge/desktop/ui/template_page.py): Updated `show_about_dialog()` (`About OsdagBridge`) to display `Developed By: Sourabh Godiyal` and credit `Sourabh Godiyal` as the individual project developer and maintainer.
- [`src/osdagbridge/desktop/ui/widgets/native_map.py`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/src/osdagbridge/desktop/ui/widgets/native_map.py): Updated tile request `UserAgentHeader` to `OsdagBridge/1.0 (Sourabh Godiyal)`.
- [`src/osdagbridge/core/reports/pdf_renderer.py`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/src/osdagbridge/core/reports/pdf_renderer.py): Updated report cover metadata table rows (`Project Ownership` and `Developer, Creator & Maintainer`) to `Sourabh Godiyal (Individual Project)` and `Developed By: Sourabh Godiyal`, while keeping the FOSSEE / IIT Bombay running footer intact.

### C. Project & Testing Documentation (28 files)
- [`README.md`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/README.md)
- [`ENGINEERING_VALUE_COMPARISON.md`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/ENGINEERING_VALUE_COMPARISON.md)
- [`FINAL_INTEGRATION_TEST_REPORT.md`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/FINAL_INTEGRATION_TEST_REPORT.md)
- [`FINAL_SUBMISSION_CHECKLIST.md`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/FINAL_SUBMISSION_CHECKLIST.md)
- [`GITHUB_COLLABORATOR_REPORT.md`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/GITHUB_COLLABORATOR_REPORT.md)
- [`GITHUB_SETUP_REPORT.md`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/GITHUB_SETUP_REPORT.md)
- [`GITHUB_SUBMISSION_REPORT.md`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/GITHUB_SUBMISSION_REPORT.md)
- [`PDF_LAYOUT_VERIFICATION.md`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/PDF_LAYOUT_VERIFICATION.md)
- [`SOURCE_CODE_REVIEW.md`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/SOURCE_CODE_REVIEW.md)
- [`TECHNICAL_CHANGES.md`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/TECHNICAL_CHANGES.md)
- [`docs/architecture.md`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/docs/architecture.md), [`docs/developer_guide.md`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/docs/developer_guide.md), [`docs/user_guide.md`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/docs/user_guide.md)
- [`documentation/Environment_Setup.md`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/documentation/Environment_Setup.md)
- [`documentation/Known_Issues.md`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/documentation/Known_Issues.md)
- [`documentation/Resume_Requirement_Checklist.md`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/documentation/Resume_Requirement_Checklist.md)
- [`documentation/Submission_Checklist.md`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/documentation/Submission_Checklist.md)
- [`documentation/Test_Execution_Instructions.md`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/documentation/Test_Execution_Instructions.md)
- [`documentation/Testing_Guide.md`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/documentation/Testing_Guide.md)
- [`demonstration/Demonstration_Steps.md`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/demonstration/Demonstration_Steps.md) & [`demonstration/Video_Link.txt`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/demonstration/Video_Link.txt)
- [`test_results/README.md`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/test_results/README.md)
- [`test_results/final_report/github_issue_drafts/BUG-001..006*.md`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/test_results/final_report/github_issue_drafts/BUG-001_unconditional_default_overwrite_in_.md) (6 issue draft files)

### D. LaTeX Sources, Regenerated PDF Reports, and Submission Archive (6 files)
- [`Report_After.tex`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/Report_After.tex) & [`Report_After.pdf`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/Report_After.pdf) *(Regenerated via ReportLab `render_pdf_report`, 467,031 bytes)*
- [`test_results/final_report/generate_pdf_report.py`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/test_results/final_report/generate_pdf_report.py)
- [`test_results/final_report/OsdagBridge_Comprehensive_Testing_Report.tex`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/test_results/final_report/OsdagBridge_Comprehensive_Testing_Report.tex) *(Regenerated, 8,747 bytes)*
- [`test_results/final_report/OsdagBridge_Comprehensive_Testing_Report.pdf`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/test_results/final_report/OsdagBridge_Comprehensive_Testing_Report.pdf) *(Regenerated via `generate_pdf_report.py`, 216,571 bytes)*
- [`OsdagBridge_Final_Submission.zip`](file:///c:/Users/acer/Desktop/images/Integrated%20Disaster%20Response%20System%20(IDRS)%20project/OsdagBridge%20Software%20Testing%20&%20Issue%20Reporting%20sourabh/OsdagBridge_Final_Submission.zip) *(Synced all 555 archive entries)*

---

## 4. Author Information Consistency & Collaborator Documentation Changes

- **Consistent Individual Attribution:** Every project-specific submission document, checklist, test report, issue draft, source module docstring, and PDF report consistently identifies **Sourabh Godiyal** (`sourabhgodiyal@gmail.com`) as the project author, developer, and maintainer.
- **Collaborator Documentation Cleanup:** All other individual collaborator references have been completely removed from all project documentation, source code docstrings, and regenerated PDF reports (`0` remaining matches).
- **Preservation of Open-Source Licensing:** FOSSEE / IIT Bombay ecosystem acknowledgements, third-party library credits, and `LICENSE` notices are preserved untouched.

---

## 5. AI-Tool Branding Audit

- Scanned all 555 repository files for AI-tool names, promotional branding, or generated-interface labels (`OpenAI`, `ChatGPT`, `Claude`, `Anthropic`, `Gemini`, `Copilot`, `Antigravity`, `LLM`, `AI-generated`).
- **Result:** `0` instances found in user-facing code or documentation. No modifications required.

---

## 6. Git Configuration & History Findings

- **Remote Origin URL:** Configured as `https://github.com/coder08sourabh/OsdagBridge-Software-Testing-Issue-Reporting-.git`.
- **Historical Commit Preservation:** Historical Git commit records in the local repository were inspected and left intact (not rewritten or fabricated).
- **Upstream References & Licensing:** Original upstream Osdag references (`https://github.com/osdag-admin/OsdagBridge.git`, `contact-osdag@fossee.in`) and open-source licensing (`LICENSE`) are preserved.

---

## 7. Final Validation & Automated Testing Results

1. **Python Syntax Validation (`compileall`):**
   - `src/`: **PASS** (0 syntax errors across all modules)
   - `tests/`: **PASS** (0 syntax errors across all test suites)
2. **PDF Report Regeneration Verification:**
   - `Report_After.pdf`: **PASS** (Regenerated via `render_pdf_report()`, 467,031 bytes)
   - `test_results/final_report/OsdagBridge_Comprehensive_Testing_Report.pdf`: **PASS** (Regenerated via `generate_pdf_report.py`, 216,571 bytes)
3. **Automated Test Suite Execution (`pytest -v tests` on Python 3.12.7):**
   - **Total Collected:** 95 tests
   - **Passed:** 90 tests (`94.7%`)
   - **Skipped (Headless GUI markers):** 5 tests (`5.3%`)
   - **Failed / Errors:** 0 (`0.0%`, Exit Code `0`)

---

## 8. Remaining Issues

- **None.** All project-level authorship, submission metadata, regenerated PDF reports, and test suites are verified and consistent.
