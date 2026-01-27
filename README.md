# GDP and Life Expectancy Portfolio Project
---
### 📌 Project Overview

This repository contains a Jupyter Notebook that explores the relationship between **GDP** (Gross Domestic Product) and **Life Expectancy** for six countries over the years 2000–2015. The analysis covers data cleaning, visualisation, statistical testing (Pearson correlation), linear regression modelling and predictive analysis.

---
### 📊 What This Project Does

- Loads and inspects the dataset (GDP and life expectancy).
- Performs exploratory data analysis (EDA) with summary statistics and plots.
- Tests linear association between GDP and life expectancy.
- Builds a linear regression model to quantify the relationship.
- Makes predictions for new GDP values.
- Visualises data and model results to aid interpretation
---
### 📁 Repository Structure
```
gdp‑life‑expectancy‑analysis/
|-- README.md.                        #Overview and documentation for this project
|-- requirements.txt		                #Python dependencies and versions
|-- data/
|  └── all_data.csv		                 #GDP and life expectancy dataset
└── notebooks/
    └── life_expectancy_gdp.ipynb    #Jupyter Notebook containing full analysis
```
---
### 📦 Requirements

To run this project, install the required Python packages listed in `requirements.txt`. This file specifies the libraries and versions used in the analysis so others can recreate your environment.

Install all dependencies at once using:

```bash
pip install -r requirements.txt
```

- numpy==2.1.3
- pandas==2.3.2
- matplotlib==3.10.0
- seaborn==0.13.2
- scipy==1.15.3
- statsmodels==0.14.4
- scikit-learn==1.6.1
- ipykernel==6.29.5
- notebook==7.3.2
  
---
### **📌 Data Source**

The dataset was provided through the **Codecademy Data Science Career Path project** and contains combined data from the **World Bank GDP** indicators and **World Health Organization life expectancy** estimates for six countries between 2000 and 2015.

---
### 📈 Key Results

- A **positive and statistically significant** correlation was found between GDP and life expectancy (*r* ≈ 0.343, *p* ≈ 0.001).
- A **simple linear regression model** quantified the relationship, showing that predicted life expectancy increases with GDP.
- The model explains a portion of the variation in life expectancy, while predictions illustrate how values change across the spectrum of GDP.

---
### 🛠️ Tools & Technologies

This project uses the following tools and libraries:

- Python
- Pandas & NumPy
- SciPy & Scikit‑Learn
- Seaborn & Matplotlib
- Jupyter Notebook
- Markdown
- Git & GitHub

---
### **🔮 Future Work**

Possible extensions include:

* Adding additional predictors such as healthcare spending or education
* Trying non‑linear models
* Time‑series or panel analysis

---
### **📜 License**

This project is available under the **MIT License**.

---
### **📌 Acknowledgements**

Thanks to **Codecademy** for the dataset and project inspiration.
