# Workflow Audit & AI Integration Setup

## 1. Weekly Workflow Audit Table

| Task Description | Classification | One-Line Rationale |
| :--- | :--- | :--- |
| **Writing custom SQL queries for DuckDB/Parquet** | Delegate to AI with review | AI generates valid query syntax quickly, but aggregations require manual verification. |
| **Structuring Streamlit UI layout and components** | Collaborate with AI | AI scaffolds interface code while I refine UX flow and data display. |
| **Evaluating ML model metrics on unseen client splits** | Just me | Model failure analysis requires domain judgment and manual error inspection. |
| **Calculating daily macronutrient & protein targets** | Fully automate | Fixed numeric formulas can be auto-calculated via simple scripts or apps. |
| **Drafting repository README files and documentation** | Delegate to AI with review | Drafts are generated fast, but require validation of paths and setup instructions. |
| **Debugging PyTorch tensor shape mismatches** | Collaborate with AI | Interactive chat helps pinpoint dimension errors faster during model training. |
| **Selecting graphic apparel & personal wardrobe choices** | Just me | Personal aesthetic choices depend entirely on subjective taste and identity. |
| **Writing baseline scikit-learn training scripts** | Delegate to AI with review | Boilerplate cross-validation code is repetitive and safe to generate with review. |
| **Planning weekly academic study schedules** | Collaborate with AI | Helps balance AI coursework and project deadlines through iterative scheduling. |
| **Cleaning raw dataset column headers and types** | Fully automate | Deterministic string formatting can be fully automated using simple script pipelines. |

---

## 2. Target Audit Tasks (For FL-02 to FL-04)

### Target Task 1: End-to-End Baseline Model Pipeline Generation
* **Definition of "Done Well":** Generates reproducible scikit-learn pipeline code with valid `GroupShuffleSplit` logic, zero data leakage, and runs without syntax errors on the first execution.

### Target Task 2: Automated SQL Feature Aggregation Query Drafting
* **Definition of "Done Well":** Writes clean DuckDB-compatible SQL queries aggregating complex temporal metrics (e.g., 90-day windows, variance) that execute with zero schema mismatches.

### Target Task 3: Interactive Streamlit Dashboard Prototyping
* **Definition of "Done Well":** Produces modular Streamlit code that renders multi-page navigation, loads Parquet files efficiently without memory spikes, and displays metric summaries correctly.

---

## 3. Tool Verification & Setup Evidence
* **Anthropic Academy Status:** Enrolled in *AI Fluency: Framework & Foundations* (Module 1 completed).
* **Claude Project Configuration:** Configured personal AI Project with custom instructions covering AI engineering background, tone preferences, and core project goals.
