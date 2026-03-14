# Customer Churn Analysis - Exploratory Data Analysis

## 📊 Project Overview

This project analyzes **customer churn patterns** in a telecommunications dataset of **7,043 customers** using Python. Through comprehensive Exploratory Data Analysis (EDA), the project identifies key factors influencing customer retention and provides data-driven insights for reducing churn rates.

---

## 🎯 Business Problem

Customer churn is a critical business metric that directly impacts revenue and profitability. Understanding **which customers are likely to leave** and **what drives their decision** enables businesses to:
- Implement targeted retention strategies
- Reduce customer acquisition costs by improving retention
- Optimize service offerings based on customer needs
- Prioritize resources for high-risk customer segments

---

## 📂 Dataset Overview

**Dataset Details:**
- **Total Records:** 7,043 customers
- **Total Features:** 21 columns
- **Target Variable:** Churn (Yes/No)

**Key Features Analyzed:**
- **Demographics:** Gender, Senior Citizen status, Partner, Dependents
- **Account Information:** Tenure, Contract type, Payment method, Paperless billing
- **Services:** Phone service, Internet service, Online security, Tech support, Streaming services
- **Financial:** Monthly charges, Total charges

---

## 🔍 Analysis Performed

### **1. Data Cleaning & Preprocessing**
- Handled missing values in `TotalCharges` column by replacing blanks with 0 for customers with tenure = 0
- Converted `TotalCharges` from object to float datatype for numerical analysis
- Transformed `SeniorCitizen` from binary (0/1) to categorical (Yes/No) for better interpretability
- Verified data quality: No duplicate records found

### **2. Exploratory Data Analysis**
- Statistical summary of numerical features (tenure, monthly charges, total charges)
- Distribution analysis of categorical variables
- Churn rate analysis across different customer segments

### **3. Churn Pattern Visualization**
Created multiple visualizations to identify churn drivers:
- **Churn by Senior Citizen Status:** Understanding age-related churn patterns
- **Churn by Payment Method:** Identifying payment types associated with higher churn
- **Tenure Analysis:** Examining relationship between customer tenure and churn behavior

---

## 💡 Key Insights

### **✅ Tenure is a Strong Retention Indicator**
> **"People who have used our services for long have stayed, and people who have used our services for short time have churned out"**

- Customers with **shorter tenure** show significantly higher churn rates
- Long-term customers demonstrate stronger loyalty and retention
- **Recommendation:** Focus retention efforts on customers in their first 12 months

### **📊 Payment Method Impact**
- Electronic check users show higher churn rates compared to other payment methods
- Contract type and billing preferences influence customer retention

### **👥 Senior Citizen Churn Patterns**
- Analysis reveals distinct churn behavior between senior and non-senior customers
- Targeted strategies may be needed for different demographic segments

---

## 🛠️ Technologies & Tools

**Programming & Libraries:**
- **Python 3.12** - Core programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization

**Development Environment:**
- **Anaconda** (anaconda-2025.12-py312)
- **Jupyter Notebook** - Interactive analysis environment

---

## 📁 Repository Structure

```
customer-churn-analysis-python/
│
├── README.md                    # Project documentation (this file)
├── CustomerChurn.ipynb          # Main Jupyter notebook with complete analysis
├── Customer Churn.csv           # Dataset (7,043 customer records)
└── visualizations/              # Generated charts (optional folder)
    ├── churn_by_seniorcitizen.png
    ├── churn_by_payment_method.png
    └── tenure_analysis.png
```

---

## 🚀 How to Run This Analysis

### **Prerequisites**
```bash
Python 3.7 or higher
Jupyter Notebook
Anaconda Distribution (recommended)
```

### **Installation Steps**

1. **Clone the repository**
```bash
git clone https://github.com/darshildave20/customer-churn-analysis-python.git
cd customer-churn-analysis-python
```

2. **Install required libraries**
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Or if using Anaconda:
```bash
conda install pandas numpy matplotlib seaborn jupyter
```

3. **Launch Jupyter Notebook**
```bash
jupyter notebook CustomerChurn.ipynb
```

4. **Run all cells** to reproduce the analysis

---

## 📊 Analysis Workflow

1. **Data Loading:** Import customer churn dataset (7,043 records, 21 features)
2. **Data Cleaning:** Handle missing values, convert data types
3. **Data Exploration:** Statistical summary and distribution analysis
4. **Feature Engineering:** Transform SeniorCitizen to categorical format
5. **Visualization:** Create countplots for churn analysis by different segments
6. **Insights Generation:** Identify key patterns and retention drivers

---

## 📈 Sample Visualizations

### Churn Distribution by Senior Citizen Status
Analysis of churn patterns between senior and non-senior customers using countplot with labeled bars.

### Payment Method Analysis
Comparison of churn rates across different payment methods (Electronic check, Mailed check, Bank transfer, Credit card).

### Tenure Impact on Retention
Visualization showing the strong correlation between customer tenure and retention rates.

*Note: All visualizations include data labels for precise value interpretation*

---

## 🎓 Skills Demonstrated

✅ **Data Cleaning:** Handling missing values, data type conversions, data quality checks  
✅ **Python Programming:** Pandas, NumPy for data manipulation  
✅ **Data Visualization:** Matplotlib, Seaborn for creating insightful charts  
✅ **Exploratory Data Analysis:** Statistical analysis and pattern recognition  
✅ **Business Analytics:** Translating data patterns into actionable business insights  
✅ **Problem-Solving:** Systematic approach to understanding customer behavior  

---

## 🔮 Future Enhancements

- [ ] Build predictive model for churn probability using machine learning
- [ ] Create customer risk segmentation (High/Medium/Low churn risk)
- [ ] Develop interactive dashboard using Plotly or Power BI
- [ ] Perform correlation analysis between all features
- [ ] Calculate customer lifetime value (CLV) analysis
- [ ] Implement A/B testing framework for retention strategies

---

## 📚 Key Learnings

- **Data Quality Matters:** Proper handling of missing values and data types is crucial for accurate analysis
- **Visualization Clarity:** Adding data labels to plots significantly improves interpretability
- **Tenure is Critical:** Early customer engagement is key to long-term retention
- **Segment-Specific Strategies:** Different customer segments require tailored retention approaches

---

## 👤 About the Analyst

**Darshil Dave**  
Senior Data Analyst | 6+ Years Experience in Supply Chain Analytics at Accenture  
Microsoft PL-300 Certified | Actively Upskilling in Python for Data Analysis

📫 **Email:** darshildave2021@gmail.com  
💼 **LinkedIn:** [Connect with me](https://linkedin.com/in/darshil-d-895394193/)  
🔗 **GitHub Portfolio:** [github.com/darshildave20](https://github.com/darshildave20)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Dataset: Telecommunications customer churn data (7,043 records)
- Tools: Anaconda Python Distribution
- Developed as part of continuous learning in Python data analysis and EDA techniques

---

**⭐ If you find this analysis helpful, please consider giving it a star!**

---

*Last Updated: March 2026*
