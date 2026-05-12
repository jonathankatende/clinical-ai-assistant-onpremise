# Clinical AI Assistant · On-Premise

A privacy-preserving clinical AI assistant allowing clinicians to interact with local clinical datasets and machine learning models using natural language.

Built as a local agentic AI framework combining:
- local machine learning models,
- conversational AI,
- SHAP explainability,
- role-based access control,
- audit logging,
- and on-premise execution.

---

## Features

- Natural language interaction with clinical datasets
- Local predictive models (Random Forest / Logistic Regression)
- SHAP-based explainability
- Cohort statistics and visualizations
- Role-based access control (RBAC)
- Audit logging
- 100% local execution (no external API calls)

---

## Example Capabilities

The assistant can:

- Predict tumor malignancy
- Explain predictions using SHAP
- Generate pie charts and cohort visualizations
- Retrieve local patient records
- Compute cohort statistics
- Interact through plain English queries

Example prompts:

```text
How many malignant cases are in the database?
Predict whether patient #12 has a malignant tumor.
Explain the prediction for patient #7.
Generate a pie chart of diagnosis classes.
