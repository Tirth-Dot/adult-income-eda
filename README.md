📊 Adult Income Dataset – Exploratory Data Analysis
📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on the Adult Income dataset (also known as the Census Income dataset). The goal is to analyze and visualize demographic and income-related patterns, often used for classification tasks such as predicting whether an individual earns more than $50K per year. The analysis is conducted in Python (Jupyter Notebook) and summarized in a Power BI–style business presentation.

📂 Project Structure
text
adult-income-eda/
├── data/
│   └── Adult.csv                 # Raw dataset
├── notebooks/
│   └── EDAanalysis.ipynb         # Main analysis notebook
├── presentations/
│   └── EDA Tirth Darji.pptx      # Insights/business presentation
├── requirements.txt              # Python dependencies (please add)
├── README.md                     # Project documentation
├── LICENSE                       # License file

🔍 Key Steps in Analysis
Data Cleaning

Handled missing values in categorical columns (workclass, occupation, native_country)

Standardized categorical variables and labels

Exploratory Analysis

Distribution of age, hours-per-week, education levels, and occupations

Income breakdown (<=50K vs >50K)

Relationships: sex, education, and occupation versus income

Correlation analysis of numerical features

Key Findings

~5.6% missing values in workclass and occupation

Majority of individuals earn <=50K

Higher education and more working hours increase odds of >50K income

Occupation strongly affects income distribution

📈 Deliverables
Power BI–Style EDA Presentation: Visual storytelling with KPIs, distributions, correlations, and insights (presentations/EDA Tirth Darji.pptx)

Jupyter Notebook: Full code, outputs, and visualizations (notebooks/EDAanalysis.ipynb)

🛠️ Tools & Technologies
Python: pandas, numpy, matplotlib

Jupyter Notebook

PowerPoint: for business presentation formatting

Power BI principles: for dashboard-style insights

🚀 How to Run
Clone the repository

text
git clone https://github.com/Tirth-Dot/adult-income-eda.git
cd adult-income-eda
Install dependencies

text
pip install -r requirements.txt
Open the Jupyter Notebook

text
jupyter notebook notebooks/EDAanalysis.ipynb
📊 Future Work
Build a classification model (Logistic Regression, Random Forest, etc.) to predict income class

Deploy an interactive dashboard using Power BI or Streamlit

Enhance missing value imputation strategies

📜 Dataset Source
Data from the UCI Machine Learning Repository – Adult Data Set.

Citation:
Dua, D. and Graff, C. (2019). UCI Machine Learning Repository. Irvine, CA: University of California, School of Information and Computer Science.

📜 License
This project is licensed under the MIT License.
