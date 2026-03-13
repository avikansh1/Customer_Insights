# Unlocking Customer Insights: A Statistical Investigation

## Project Overview
This project analyzes customer demographic and behavioral data to uncover spending patterns, engagement trends, and statistically significant relationships between customer attributes.

The analysis was performed as part of a **Data Analytics with GenAI – Statistics Project Assessment**.  
Using descriptive statistics, exploratory data analysis, visualizations, and hypothesis testing, this project aims to support data-driven business decision-making.

---

## Business Problem
A mid-sized retail company has customer data but lacks clarity on what insights it contains.  
The goal of this project is to:

- understand customer demographics and behavior
- analyze spending and engagement patterns
- compare customer behavior across groups
- test business assumptions using statistical methods
- provide actionable business recommendations

---

## Dataset Description
The dataset contains **10,675 records** and includes the following columns:

- **CustomerID** – Unique customer identifier  
- **Name** – Customer name  
- **State** – State where the customer resides  
- **Education** – Highest education level attained  
- **Gender** – Gender identity  
- **Age** – Customer age  
- **Married** – Marital status  
- **NumPets** – Number of pets owned  
- **JoinDate** – Customer join date  
- **TransactionDate** – Transaction date  
- **MonthlySpend** – Monthly customer spending  
- **DaysSinceLastInteraction** – Number of days since the last interaction  

---

## Tools & Libraries Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **SciPy**

---

## Project Workflow

### 1. Data Understanding
- Loaded and explored the dataset
- Checked data types, null values, and unique values
- Identified numerical and categorical variables

### 2. Descriptive Statistics
- Calculated mean, median, and standard deviation
- Found mode for categorical variables
- Summarized age, spending, and customer activity patterns

### 3. Data Visualization
- Histograms for Age and MonthlySpend
- Boxplots for Age and MonthlySpend
- Bar charts for Gender, Education, and State
- Scatterplot for Age vs MonthlySpend
- KDE plot for MonthlySpend by customer groups

### 4. Bivariate Analysis
- Correlation matrix for numerical variables
- Crosstab analysis for Gender vs Married
- Grouped statistics for MonthlySpend by State, Education, and Gender

### 5. Hypothesis Testing
The following statistical tests were performed:

- **Independent T-Test**  
  - Do males and females spend differently?

- **One-Way ANOVA**  
  - Does education level impact average monthly spend?
  - Does state-wise spend vary significantly?

- **Chi-Square Test**  
  - Is marital status related to the number of pets owned?

- **Correlation Test**  
  - Are older people less active?

---

## Key Insights
- Customer spending behavior shows **high variability**, with a small group of customers spending significantly more than average.
- The **average customer age is around 49 years**, indicating a mature and diverse customer base.
- Many customers show **long inactivity periods**, suggesting opportunities for customer re-engagement.
- Statistical testing suggests that **gender and education level do not significantly affect monthly spending** in this dataset.
- Customer behavior varies across **different states**, supporting the need for geographic segmentation.

---

## Business Recommendations
- Identify and retain **high-value customers** using loyalty programs and personalized offers.
- Launch **re-engagement campaigns** for inactive customers.
- Apply **customer segmentation** based on spending behavior.
- Use **region-specific marketing strategies** for different states.
- Support decisions with **data-driven analysis rather than assumptions**.

---

## Repository Structure
```bash
Customer_Insights/
│
├── notebooks/
│   └── Customer_Insights.ipynb
├── README.md
├── .gitignore
