# Retention360: Employee Attrition Analysis & Prediction

### Project Overview

Retention360 is a data-driven project aimed at understanding and predicting employee attrition. The goal is to help organizations identify factors influencing employee turnover and implement strategic measures to enhance retention. This project leverages machine learning models to analyze employee data, uncover patterns, and predict attrition risks.

### Problem Statement

Employee attrition is a critical challenge for organizations, leading to financial and knowledge losses. Common reasons for attrition include:
- Low salaries
- Limited career growth opportunities
- Poor management
- Work-life balance issues
- Lack of recognition
- High workload and burnout

By predicting which employees are at risk of leaving, HR teams can take proactive measures to retain talent and optimize workforce planning.

### Objectives

- Analyze key factors driving employee attrition.
- Identify trends in job satisfaction, compensation, and work-life balance.
- Develop predictive models to assess attrition risk.
- Provide actionable recommendations for improving retention.

### Dataset
- Source: HR Employee Attrition Dataset
- Key Features: Age, Salary, Job Role, Job Satisfaction, Work-Life Balance, Overtime, Promotion History, etc.

### Key Milestones

1. Data Collection & Preprocessing
- Handled missing values and removed irrelevant columns.
- Encoded categorical variables and standardized numerical features.
- Performed Exploratory Data Analysis (EDA) to understand trends.

2. Feature Engineering & Analysis
- Identified key attrition factors such as salary, overtime, and job satisfaction.
- Created new features like "Income-to-Experience Ratio" and "Job Stability Index."
- Conducted correlation analysis to detect strong relationships.

3. Model Selection & Training
- Tested multiple ML models:
- Logistic Regression (86% accuracy, weak recall for attrition cases)
- Random Forest (92% accuracy, low sensitivity for attrition cases)
- XGBoost (91% accuracy, best balance but required improvements)

Addressed class imbalance using class weighting and SMOTE.

4. Findings & Insights
- Employees with low salaries and low job satisfaction are more likely to leave.
- Gen Z employees have the highest turnover rates, while Millennials are more stable.
- Employees working overtime show higher attrition rates due to burnout.
- Lack of career growth opportunities significantly increases turnover.

### Technology Stack

- Programming Language: Python
- Libraries: Pandas, NumPy, Scikit-learn, XGBoost, Seaborn, Matplotlib
- Tools: Jupyter Notebook, GitHub

### Implementation Steps
1. Data Preprocessing and Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Training and Evaluation
5. Results Interpretation
6. Project Report

### Recommendations & Solutions

1. Tailored Strategies
- Implement personalized career development plans.
- Use employee feedback to improve workplace policies.

2. Work Arrangements
- Offer flexible work schedules and hybrid work models.
- Introduce work-life balance initiatives to reduce burnout.

3. Recognition Programs
- Develop structured recognition and reward programs.
- Establish performance-based incentives and bonuses.

4. Salary Adjustments
- Conduct market-based salary evaluations.
- Provide competitive pay and stock options to retain top talent.

### Contributing

I welcome contributions! If you have ideas for improving this project:

1. Fork the repository.
2. Create a new branch (feature-branch).
3. Commit your changes.
4. Submit a Pull Request.

### License

This project is licensed under the MIT License - see the LICENSE file for details.

### Contact

For queries or collaborations, reach out via:
- Email: himunagapure114@gmail.com
- LinkedIn: https://www.linkedin.com/in/himanshunagapure/
