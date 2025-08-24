# 📊 Adult Income Dataset – Exploratory Data Analysis

## 📌 Project Overview

This project performs comprehensive **Exploratory Data Analysis (EDA)** on the Adult Income dataset (also known as the Census Income dataset). The primary objective is to analyze and visualize demographic and income-related patterns, providing insights that are commonly used for classification tasks such as predicting whether an individual earns more than $50K per year.

The analysis is conducted using **Python** in Jupyter Notebook format and findings are summarized in a professional **Power BI-style business presentation**.

---

## 📂 Project Structure

```
adult-income-eda/
├── data/
│   └── Adult.csv                 # Raw dataset
├── notebooks/
│   └── EDAanalysis.ipynb         # Main analysis notebook
├── presentations/
│   └── EDA Tirth Darji.pptx      # Insights/business presentation
├── requirements.txt              # Python dependencies
├── README.md                     # Project documentation
└── LICENSE                       # License file
```

---

## 🔍 Key Steps in Analysis

### 🧹 Data Cleaning
- **Missing Values**: Handled missing values in categorical columns (`workclass`, `occupation`, `native_country`)
- **Data Standardization**: Standardized categorical variables and labels for consistency
- **Data Quality Assessment**: Identified and addressed data inconsistencies

### 📊 Exploratory Analysis
- **Demographic Distributions**: Analysis of age, hours-per-week, education levels, and occupations
- **Income Breakdown**: Detailed analysis of income distribution (<=50K vs >50K)
- **Feature Relationships**: Investigated relationships between sex, education, occupation, and income
- **Correlation Analysis**: Statistical analysis of numerical features and their interdependencies

### 🎯 Key Findings
- **Missing Data**: ~5.6% missing values identified in workclass and occupation columns
- **Income Distribution**: Majority of individuals in the dataset earn <=50K annually
- **Education Impact**: Higher education levels significantly increase the probability of >50K income
- **Work Hours Correlation**: Increased working hours positively correlate with higher income brackets
- **Occupational Influence**: Job type strongly affects income distribution patterns

---

## 📈 Project Deliverables

| Deliverable | Description | Location |
|-------------|-------------|----------|
| **Power BI-Style Presentation** | Visual storytelling with KPIs, distributions, correlations, and actionable insights | `presentations/EDA Tirth Darji.pptx` |
| **Jupyter Notebook** | Complete analysis with code, outputs, visualizations, and detailed explanations | `notebooks/EDAanalysis.ipynb` |
| **Dataset** | Clean, processed Adult Income dataset ready for analysis | `data/Adult.csv` |

---

## 🛠️ Tools & Technologies

- **Programming Language**: Python 3.x
- **Data Analysis**: pandas, numpy, scipy
- **Visualization**: matplotlib, seaborn, plotly
- **Environment**: Jupyter Notebook
- **Presentation**: PowerPoint with Power BI design principles
- **Version Control**: Git & GitHub

---

## 🚀 How to Run

### Prerequisites
- Python 3.7 or higher
- Jupyter Notebook or JupyterLab
- Git (for cloning)

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Tirth-Dot/adult-income-eda.git
   cd adult-income-eda
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
   
   *Note: If `requirements.txt` is not available, install manually:*
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter plotly
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook notebooks/EDAanalysis.ipynb
   ```

4. **Run the analysis**
   - Execute all cells in the notebook
   - Review outputs and visualizations
   - Examine the generated insights

---

## 📊 Future Enhancements

- [ ] **Machine Learning Models**: Implement classification algorithms (Logistic Regression, Random Forest, XGBoost) for income prediction
- [ ] **Interactive Dashboard**: Deploy using Streamlit or Dash for real-time data exploration
- [ ] **Advanced Analytics**: Implement feature engineering and advanced statistical analysis
- [ ] **Missing Value Strategies**: Enhance imputation techniques using advanced methods
- [ ] **Model Deployment**: Create API endpoints for model serving
- [ ] **Automated Reporting**: Implement automated report generation pipeline

---

## 📊 Dataset Information

**Source**: [UCI Machine Learning Repository – Adult Data Set](https://archive.ics.uci.edu/ml/datasets/adult)

**Features**: 14 attributes including age, workclass, education, marital-status, occupation, relationship, race, sex, capital-gain, capital-loss, hours-per-week, native-country, and income

**Target Variable**: Income (<=50K, >50K)

**Dataset Size**: 32,561 instances

### Citation
Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Tirth Darji**  
- GitHub: [@Tirth-Dot](https://github.com/Tirth-Dot)
- LinkedIn: [Connect with me](https://linkedin.com/in/tirth-darji)

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/Tirth-Dot/adult-income-eda/issues).

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## ⭐ Show your support

Give a ⭐️ if this project helped you!

---

*Last Updated: August 2025*
