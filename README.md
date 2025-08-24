# 📊 Adult Income Dataset – Exploratory Data Analysis  

## 📌 Project Overview  
This project performs **Exploratory Data Analysis (EDA)** on the **Adult Income dataset** (also known as the Census Income dataset). The dataset is widely used for classification tasks such as predicting whether an individual earns more than **$50K per year** based on demographic attributes.  

The analysis was conducted using **Python (Jupyter Notebook)** and converted into a **Power BI–style presentation** for business storytelling.  

---

## 📂 Project Structure  
```
├── Adult.csv                          # Dataset
├── EDAanalysis.ipynb                  # Jupyter Notebook (EDA code + outputs)
├── EDAanalysis_PowerBI_Presentation.pptx   # Power BI–style insights presentation
├── EDAanalysis_Code_and_Output.pptx   # Notebook code and outputs presentation
├── EDAanalysis_Code_Only.pptx         # Notebook code-only presentation
└── README.md                          # Project documentation
```

---

## 🔍 Key Steps in Analysis  
1. **Data Cleaning**
   - Removed/handled missing values in `workclass`, `occupation`, and `native_country`.  
   - Standardized categorical values.  

2. **Exploratory Analysis**
   - Distribution of **age**, **hours worked per week**, **education levels**, and **occupations**.  
   - Income distribution (`<=50K` vs `>50K`).  
   - Relationship of demographic variables (sex, education, occupation) with income.  
   - Correlation analysis of numeric variables (age, education-num, hours-per-week, capital-gain/loss).  

3. **Key Findings**
   - Around **5.6% missing values** in `workclass` and `occupation`.  
   - Majority of individuals earn **<=50K**.  
   - Higher education and longer working hours increase chances of earning **>50K**.  
   - Occupation type strongly influences income distribution.  

---

## 📈 Deliverables  
- **📊 Power BI–style EDA Presentation** → Visual storytelling with KPIs, distributions, correlations, and insights.  
- **💻 Notebook Code & Outputs Presentation** → Step-by-step record of code and results.  
- **📝 Code Only Presentation** → Clean export of Jupyter Notebook code cells.  

---

## 🛠️ Tools & Technologies  
- **Python** (pandas, numpy, matplotlib)  
- **Jupyter Notebook**  
- **PowerPoint (pptx automation)**  
- **Power BI design principles** for dashboard-style presentations  

---

## 🚀 How to Run  
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/adult-income-eda.git
   cd adult-income-eda
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook EDAanalysis.ipynb
   ```

---

## 📊 Future Work  
- Build a **classification model** (Logistic Regression, Random Forest, etc.) to predict income.  
- Deploy an **interactive dashboard** in Power BI / Streamlit.  
- Enhance missing value imputation strategies.  

---

## 📜 Dataset Source  
The **Adult Income dataset** comes from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/adult).  

**Citation:**  
Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.  

---

## 📜 License  
This project is licensed under the **MIT License**.  
