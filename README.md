# Udemy Course Success Analysis

## Overview
This project analyzes **209,000+ Udemy courses** to uncover what makes a course **profitable** and **highly rated**. Using **Python**, **pandas**, **data visualization**, and **multiple regression modeling**, we investigated which factors — such as price, content length, reviews, and subscribers — influence both **revenue** and **learner satisfaction**.

The findings provide actionable insights for instructors, students, and content creators while demonstrating advanced data analytics techniques.

---

## Key Features
- Dataset: 209,000+ Udemy courses from Kaggle  
- Exploratory Data Analysis: Distribution plots, correlations, and feature impact analysis  
- Modeling Approach: Multiple Linear Regression for predicting:
  - Revenue (profitability)
  - Average Ratings (learner satisfaction)
- Performance Metrics:
  - R² for Revenue: **0.227**
  - R² for Ratings: **0.050**
- Core Technologies: Python, Pandas, Matplotlib, Scikit-learn, Statsmodels  
- Collaboration: Team project focused on statistical modeling and business insights  

---

## Project Structure
udemy-course-success-analysis/
│── data/                       # (Optional sample data or Kaggle link)
│── notebooks/
│   └── Udemy_Analysis.ipynb    # Cleaned, structured notebook
│── reports/
│   └── Computational_Statistics_Project.pdf  # Final project report
│── images/                     # Charts & visualizations (optional)
│── requirements.txt            # Python dependencies
│── README.md                  # Project documentation

---

## Insights and Findings
- Pricing and content length are strong predictors of profitability.  
- Subscribers and reviews significantly affect learner satisfaction.  
- Predicting overall success remains challenging due to hidden factors like teaching style and marketing strategy.  
- Human-driven preferences limit predictive power, which explains the relatively low R² scores.

---

## Methodology
1. **Data Preparation**
   - Removed courses with invalid ratings (<3)
   - Filtered extreme outliers in revenue  
   - Cleaned categorical variables like category and language  

2. **Exploratory Data Analysis**
   - Analyzed revenue distributions and correlations
   - Plotted feature impacts on profitability and satisfaction  

3. **Model Development**
   - Built multiple regression models
   - Evaluated model performance using R² and residual diagnostics  

4. **Conclusion**
   - Identified actionable factors while recognizing modeling limitations  

---

## How to Run the Project
1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/udemy-course-success-analysis.git
cd udemy-course-success-analysis

2.Install dependencies:
pip install -r requirements.txt

3.	Open the notebook:
jupyter notebook notebooks/Udemy_Analysis.ipynb

Technologies Used
	•	Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels)
	•	Jupyter Notebook
	•	Multiple Linear Regression
	•	Statistical Hypothesis Testing
	•	Data Cleaning and Visualization

⸻

Collaborators
	•	Benjamin Morris
	•	Inbar Sapir
	•	Yehuda Wexler

⸻

Future Improvements
	•	Add predictive models like Random Forest or XGBoost to improve accuracy.
	•	Deploy an interactive dashboard using Streamlit for live revenue predictions.
	•	Automate feature selection for scalability.
