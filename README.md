# Lead_Scoring_Case_Study
</br>

## 📌 Project Description

This project focuses on building a Leads Conversion Classification System for X Education, an online course provider. The goal is to develop a predictive model that determines whether a lead will convert based on various factors collected during the client inquiry phase. With a current conversion rate of 30%, the company aims to improve efficiency by prioritizing high-potential leads, targeting an 80%+ conversion rate. The dataset consists of 9,000+ records from past leads, with key features like Lead Source, Total Time Spent on Website, and Last Activity. This project involves data preprocessing, feature engineering, model development, evaluation, and business insights, providing actionable recommendations to enhance lead conversion.

## 🔧 Tech Stack 

- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Statsmodels  
- **Dataset:** `Leads.csv` (attached)  
- **Dataset Description:** `Leads Data Dictionary.xlsx` (attached)  
- **Model Used:** Logistic Regression

## 🔍 Exploratory Data Analysis (EDA)

- **Data Cleaning & Preprocessing:** Handled missing values, outliers, and feature scaling.
- **Feature Engineering:** Created new variables based on existing data.
- **Visualization:** Used Matplotlib and Seaborn to explore trends in lead conversion.

## 🚀 Model Training & Evaluation

- **Train-Test Split:** 70% training, 30% testing.
- **Model Used:** Logistic Regression
- **Evaluation Metrics:**
  - Accuracy Score
  - Precision, Recall, F1-score
  - Confusion Matrix
  - ROC-AUC Curve

## ⚡ Key Findings & Insights

### Factors that increase the probability of lead conversion:
- **Tags_Closed by Horizzon:** Leads with this tag have the highest chance of converting.
- **Tags_Lost to EINS:** Leads marked as lost to EINS have a very high probability of conversion.
- **Tags_Will revert after reading the email:** Leads with this status tend to have a good chance of converting.
- **Lead_Source_Welingak Website:** Leads sourced from this website show strong conversion potential.

### Factors that indicate a lead will not convert:
- **Tags_Switched off:** Leads with this status are highly unlikely to convert.
- **Tags_Ringing:** Leads that do not pick up calls are mostly non-convertible.

## 🛠 How to Run
**Clone the repository:**
   ```bash
   git clone <https://github.com/Om-Shirke/Lead_Conversion_Prediction.git>
```
## 📈 Future Improvements

- Implement advanced models like Random Forest, XGBoost for better accuracy.
- Tune hyperparameters using GridSearchCV.
- Incorporate real-time lead scoring based on live data.

## 📂 Project Structure  

| File Name                               | Description                                      |
|-----------------------------------------|------------------------------------------------|
| `data.csv`                              | Previous leads dataset               |
| `data_dictionary.xlsx`                  | Column descriptions and data definitions       |
| `Lead Scoring Case Study Summary.pdf`   | Complete procedure and conclusions of the study |
| `Lead Scoring Case Study.ipynb`         | Complete study processes in Jupyter with Python |
| `Lead Scoring Case Study Presentation.pdf` | Case study with visualizations and business insights |
| `README.md`                             | Project documentation                          |


## 📢 Credits & References

- **Project by:** Om Shirke

