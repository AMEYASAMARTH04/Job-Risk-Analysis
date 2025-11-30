# Job-Risk-Analysis
This dashboard analyzes the impact of AI on future job stability by combining automation probability, experience, salary, and risk category. It highlights high-risk roles, compares predicted vs actual impact, and visualizes job vulnerability trends for 2030 to support data-driven workforce decisions.

🚀 Project Overview

The goal of this project is to forecast the risk of job automation and compare actual vs predicted trends across industries.
Using structured job data, the machine learning model predicts:

Automation Probability (2030)

Risk Category (High / Medium / Low)

Salary Trends

Average Experience

AI Impact Percentage

These insights are visualized in a modern, user-friendly dashboard that enables deep exploration of job vulnerabilities.

📊 Key Features
✅ 1. End-to-End ML Pipeline

Data cleaning, preprocessing, and encoding

Train-test split and model training

Evaluation using accuracy & regression metrics

Prediction of job automation levels for 2030

✅ 2. Job Risk Classification

Model assigns each role into:

High Risk

Medium Risk

Low Risk

based on AI impact.

✅ 3. Power BI Dashboard

The dashboard includes:

Summary cards (Risk Score, Experience, Salary, AI Impact)

Actual vs Predicted comparison table

Automation probability trend by job

Job count vs Salary distribution

Job filtering feature

✅ 4. Actionable Insights

Identify jobs most vulnerable to automation

Compare salary vs risk

Understand which industries are safer

Support upskilling and career planning decisions

🧠 Tech Stack

Python (Pandas, NumPy, Scikit-learn)

Machine Learning Models

Power BI for visualization

CSV Dataset for job and automation analysis

📁 Project Structure
AI_Impact_on_Jobs_2030/
│
├── data/
│   └── AI_Impact_on_Jobs_2030.csv
│
├── model/
│   ├── training_code.py
│   ├── predictions.csv
│   └── saved_model.pkl
│
├── dashboard/
│   └── Job_Risk_Analysis.pbix
│
└── README.md

📌 Insights From the Dashboard

Jobs like Retail Worker, Security Guard, Construction Worker show very high automation risk.

Professions such as AI Engineer, Doctor, Research Scientist remain least affected.

Higher automation risk often aligns with lower salaries and task repetition.

Roles requiring creativity, problem-solving, and human interaction are more future-proof.

🧩 How to Use

Run the Python script to train the model.

Generate predicted values for all job titles.

Load the Power BI file and refresh the data source.

Explore trends, insights, and risk visualizations interactively.

🤝 Contributions

Contributions, improvements, and feature additions are welcome!
Feel free to submit a pull request.

📬 Contact

For queries, collaborations, or discussions:
Amey Samarth
