# Financial-Risk-Modeling
 Financial risk modeling using German Credit data with EDA, ML models, and validation metrics.
# Financial Risk Analysis & Credit Default Assessment (Python)

## Business Context
Banks and financial institutions must assess loan applications accurately to minimize credit default risk. Incorrect risk assessment can lead to financial loss, regulatory impact, and reputational risk.

This project focuses on analyzing customer credit data to support **risk-based decision making** through **exploratory data analysis, statistical assessment, and model validation**, aligned with financial risk and governance expectations.

---

## Objective
- Understand business requirements related to credit risk assessment  
- Perform exploratory data analysis (EDA) to identify key risk drivers  
- Apply quantitative and qualitative analysis to compare customer risk profiles  
- Validate analytical findings using predictive models  
- Deliver clear, explainable, and business-focused insights  

---

## Dataset
- **German Credit Risk Dataset** (UCI Machine Learning Repository)
- **Records:** 1,000 customers  
- **Attributes:** 20+ financial, behavioral, and demographic variables  
- **Target Variable:** `CreditRisk` (Good / Bad)

---

## Tools & Technologies
- **Python**
  - Pandas, NumPy
  - Matplotlib, Seaborn
  - Scikit-learn
- **Techniques**
  - Exploratory Data Analysis (EDA)
  - Statistical Analysis
  - Risk Driver Identification
  - Model Validation

---

## Methodology

### 1. Data Understanding & Preparation
- Loaded and inspected raw credit data
- Performed data quality checks and validated distributions
- Encoded categorical variables to support analysis and modeling

### 2. Exploratory Data Analysis (EDA)
- Conducted **univariate analysis** to understand individual feature behavior  
- Performed **bivariate analysis** using groupby analysis, bar plots, box plots, and correlation analysis  
- Compared patterns across **Good vs Bad credit customers**

### 3. Risk Driver Identification
- Identified key variables influencing credit default risk, including:
  - Credit Amount
  - Loan Duration
  - Age

### 4. Model Development & Validation
- Developed baseline predictive models:
  - **Logistic Regression** (explainable, regulatory-aligned)
  - **Random Forest** (performance benchmarking)
- Evaluated model performance using:
  - Accuracy
  - Confusion Matrix
  - ROC-AUC

### 5. Insight Communication & Governance
- Created multiple visualizations to improve interpretability
- Translated analytical outputs into actionable business insights
- Followed a structured and reproducible analytics workflow aligned with governance expectations

---

## Key Insights
- Higher credit amounts and longer loan durations are associated with increased default risk  
- Risk behavior varies across customer segments  
- Explainable models support transparency, while ensemble models enhance predictive performance  

---

## Outcomes
- Identified key credit risk drivers influencing default behavior  
- Supported **risk-based credit assessment** through data-driven insights  
- Demonstrated end-to-end analytical capability aligned with **financial risk, technology delivery, and compliance needs**

---

## Project Structure
Financial-Risk-Analysis/
│
├── data/
│ └── german.data.csv
│
├── notebooks/
│ └── Risk_Model.ipynb
│
├── outputs/
│ └── Age.png
│ └── CreditAmount.png
│ └── Duration.png
│ └── Feature_Importance.png
│ └── Heatmap.png
│ └── LogisticRegression.png
│ └── ROC_Curve.png
│ └── RandomForestClassifier.png
│ └── credit_risk_distribution.png
│
├── README.md


---

## Key Skills Demonstrated
- Financial Risk Analysis  
- Exploratory Data Analysis (EDA)  
- Statistical & Quantitative Assessment  
- Model Validation & Interpretation  
- Business & Stakeholder Communication  
- Governance-Aligned Analytics  

---

## Conclusion
This project demonstrates the application of Python-based analytics to support **financial risk assessment**, combining technical analysis with business understanding, governance awareness, and clear communication—aligned with expectations for Analyst Trainee roles.
