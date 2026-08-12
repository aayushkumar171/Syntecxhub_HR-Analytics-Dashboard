# 👥 HR Analytics Dashboard — Project 2

An HR analytics project that analyzes employee data to understand attrition patterns, key drivers of turnover, and department/role-level trends — presented through an interactive dashboard for HR decision-making.

## 🎯 Objective
Analyze employee data (salary, department, experience, etc.) to identify patterns in attrition, uncover key contributing factors through correlation analysis, and build KPIs and a dashboard to support HR decisions.

## ✅ Project Tasks
- Analyze employee dataset (salary, department, experience)
- Identify patterns in employee attrition
- Perform correlation analysis to find key factors
- Compare attrition across departments and roles
- Build KPIs like attrition rate, retention rate
- Create an HR dashboard for decision-making

## 🗂️ Repository Structure
```
hr-analytics-dashboard/
│
├── notebooks/
│   └── Project_2.ipynb           # Data cleaning, EDA, correlation analysis
├── data/
│   ├── raw_employee_data.csv     # Raw employee dataset
│   └── processed_employee_data.csv  # Cleaned dataset with derived KPIs
├── dashboard/
│   └── HR_dashboard.pbix         # Power BI / Tableau dashboard
├── images/
│   └── project_overview.png      # Project brief / description
├── requirements.txt              # Python dependencies
└── README.md
```

## 🛠️ Tools & Technologies
- **Python** (pandas, numpy, matplotlib, seaborn) — data cleaning, EDA & correlation analysis
- **Jupyter Notebook** — analysis workflow
- **Power BI / Tableau** — HR dashboard for decision-making

## 🔍 Workflow
1. **Import Libraries & Load Employee Data**
2. **Data Cleaning** — handle missing values, standardize department/role labels, fix data types
3. **Exploratory Data Analysis** — distribution of salary, experience, department, and attrition
4. **Correlation Analysis** — identify which factors (salary, tenure, satisfaction, overtime, etc.) correlate most with attrition
5. **Departmental & Role-Level Comparison** — attrition breakdown by department and job role
6. **KPI Calculation**
   - **Attrition Rate** — % of employees who left in the period
   - **Retention Rate** — % of employees retained
   - Additional KPIs: average tenure, average salary by department, headcount by role
7. **Dashboard** — interactive visuals summarizing attrition drivers and KPIs for HR stakeholders

## 📈 Dashboard
Visual summary of attrition rate, retention rate, and the key factors driving employee turnover, broken down by department and role.

## 🚀 How to Run
1. Clone the repo
   ```bash
   git clone https://github.com/<your-username>/hr-analytics-dashboard.git
   cd hr-analytics-dashboard
   ```
2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```
3. Open `notebooks/Project_2.ipynb` in Jupyter Notebook / JupyterLab and run the cells
4. Open the dashboard file in Power BI Desktop / Tableau to explore the visuals

## 📌 Notes
- Update the raw data source path in the notebook if you re-run it with your own dataset.
- Correlation analysis assumes numeric/encoded fields for categorical variables (e.g. department, role) — encoding steps are handled in the notebook.
