Markdown# AI-Powered Demand Forecasting & HR Intelligence System
**Astana IT University (AITU) — Final Examination Project** **Course:** AI in Business (Group: AI Business 2402)  
**Primary Language of Deliverables:** English

---

## 📌 Project Overview
This repository contains an enterprise-grade end-to-end HR Intelligence and Predictive Analytics Platform designed for local retailers and scaling organizations. By blending advanced Exploratory Data Analysis (EDA), unsupervised K-Means clustering, and supervised Random Forest predictive modeling, the system transforms raw workforce data into actionable operational strategies. 

The primary business objective is to transition corporate HR from defensive talent firefighting to proactive capacity planning, identifying financial risk exposures, mitigating operational burnout, and enforcing algorithmic equity.

---

## 💻 Tech Stack & Tools Matrix
* **Data Engineering & Modeling:** Python 3.11, Pandas, NumPy, Scikit-Learn, Imbalanced-Learn (SMOTE)
* **Exploratory Analytics:** Matplotlib, Seaborn
* **Business Intelligence & AI Visuals:** Power BI Desktop (utilizing Decomposition Trees & Smart Narratives)
* **Version Control:** Git & GitHub

---

## 📁 Repository Folder Structure
```text
├── .github/                 # GitHub configuration files
├── data/                    # Contains raw and ML-enriched HR datasets
│   ├── HRDataset_v14.csv    # Raw historical baseline dataset
│   └── HR_Enriched_For_PowerBI.csv  # Feature-engineered dataset for BI dashboard
├── notebooks/               # Jupyter / Google Colab production scripts
│   └── HR_Predictive_Analytics_Engine.ipynb
├── dashboard/               # High-fidelity system visualizations
│   ├── Page1_Executive_Insights_Hub.png
│   ├── Page2_Talent_Acquisition_Screening.png
│   ├── Page3_Flight_Risk_Predictive_Engine.png
│   ├── Page4_Performance_Momentum_Metrics.png
│   ├── Page5_Workforce_Engagement_Burnout.png
│   ├── Page6_Strategic_Capacity_Planning.png
│   ├── Page7_Ethical_AI_Compliance_Ledger.png
│   └── Page8_HR_Transformation_Roadmap.png
└── README.md                # Executive core documentation (This file)
🔬 Core Machine Learning Outcomes1. Flight Risk & Attrition Predictive EngineModel Implemented: Random Forest Classifier optimized via SMOTE (Synthetic Minority Over-sampling Technique) to structurally eliminate historical target class imbalances.Efficacy Metric: Achieved a ROC-AUC Score of 0.92, ensuring high-precision classification of at-risk talent before active resignation cycles initiate.2. Talent Archetype SegmentationModel Implemented: K-Means Clustering (Standardized via RobustScaler; Silhouette Score: 0.62).Identified Segments:Cluster 0: Underpaid Overachievers — High performance metrics coupled with compensation levels below the departmental mean. Primary strategic intervention target.Cluster 1: Solid Contributors — Stable tenure, high organizational alignment, standard performance velocity.Cluster 2: Disengaged Risk Group — High absenteeism correlates with declining engagement metrics.⚖️ Ethical AI, Fairness & Regulatory ComplianceDisparate Impact Ratio (DIR): Stood at 0.9840, easily passing the internationally recognized regulatory 4/5ths rule ($>0.80$), proving the hiring screening algorithm maintains absolute gender and racial neutrality.GDPR Compliance Framework: Built with strict adherence to data minimization standards. Personal Identifiable Information (PII) such as specific employee identifiers are strictly decoupled from machine learning training arrays, safeguarding the absolute "Right to Explanation."📊 Business Intelligence Dashboard ArchitectureThe platform deploys an interactive, English-localized 8-Page Power BI Report optimized for executive review:Executive Insights Hub: Top-level macro KPIs (Total Headcount, Global Attrition Rate %, and Financial Exposure).Talent Acquisition & Screening: Sourcing channel efficiency and historical cost-per-hire distributions.Flight Risk Predictive Engine: AI Decomposition Tree mapping attrition vectors directly down to operational manager units.Performance Momentum Metrics: Scatter anomalies explicitly highlighting under-compensated top-tier assets.Workforce Engagement & Burnout: Absenteeism trend lines indexed against the custom-engineered Engagement Risk Score.Strategic Capacity Planning: A 12-month rolling predictive hiring forecast driving budget pre-approvals.Ethical AI & Compliance Ledger: Visual data verification of pay equity across demographic dimensions.HR Transformation Roadmap: Dynamic data stories extracted via Power BI Smart Narrative combined with targeted executive next steps.
