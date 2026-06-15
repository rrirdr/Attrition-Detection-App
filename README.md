# Attrition-Detector-App

A Streamlit-powered data science solution engineered to transform workforce attrition management from a reactive, "post-mortem" reporting process into a proactive early-warning system. This platform provides business operators and people managers with data-driven tools to mitigate turnover, balance workloads, and minimize financial exposure.

## The Core Problem & Operational Impact
In high-volume industries like Business Process Outsourcing (BPO), employee turnover triggers a severe operational domino effect. When an individual resigns, it imposes a "survivor tax" on remaining staff—driving burnout, shift extensions, and performance degradation. Financially, replacement costs, recruitment fees, and lost production capacity directly impact organizational profitability. 

Traditionally, people managers only discover an employee is unhappy when a resignation letter lands on their desk. **Project Omni-Retention** bridges the gap between raw data and real-time operational intervention.

## Key System Features

* **Executive Summary:** An interactive macro dashboard tracking baseline active headcounts against historical departures to establish structural churn trends.
* **Attrition Drivers & Well-being Analytics:** An exploratory data engine that captures patterns behind departures, highlighting deep correlations between shift distributions, job satisfaction thresholds, and lifecycle milestones.
* **Model Intelligence Control Room:** The predictive core of the app. It compares **8 different machine learning classification models**, explicitly optimizing for **Recall over simple accuracy** to ensure at-risk employees are rarely missed. Transparent metrics include feature importance weights, dynamic ROC curves, and confusion matrices.
* **Predictive Risk Ledger (Employees to Review):** A structured operational workflow categorizing the active workforce into *High, Medium, and Low-risk* brackets based on calculated flight probabilities, complete with offline export capabilities.
* **Risk Predictor Sandbox (Beta):** A workspace allowing managers to adjust core operational levers (e.g., boosting a segment's work-life balance or job satisfaction) to instantly simulate mitigation strategies.
* **Financial Attrition Simulator:** A dynamic run-rate model that translates headcount turnover into a 12-month forward-looking dollar bleed. It flags cost exposure early, proving the definitive ROI of retention efforts before capital loss occurs.

## Future Roadmap
* **Hyperparameter Tuning:** Implementing systematic grid/random search workflows to maximize minority-class F1-scores.
* **Dimensionality Reduction:** Applying Principal Component Analysis (PCA) to decouple highly collinear demographic features.
