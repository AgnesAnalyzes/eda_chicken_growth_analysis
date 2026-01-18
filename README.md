# Exploratory Data Analysis: Chicken Growth & Feed Impact

## Project Overview
This project explores the growth patterns of chickens over time and analyzes how different feed categories influence weight development at various life stages.

Using **exploratory data analysis (EDA)** and **data visualization**, the goal is to uncover trends, detect outliers, and derive insights that could support data-driven decisions in agricultural or livestock management contexts.

---

## Business / Analytical Objective
The analysis aims to answer the following key questions:

- How does chicken weight evolve with age?
- Do different feed categories lead to significantly different growth patterns?
- At which life stages do feed-related differences become most visible?
- Are there anomalies or outliers that may indicate health issues or data quality problems?

---

## Dataset Description
The dataset contains longitudinal measurements of chicken growth, including:

- **Age** (in days)
- **Weight**
- **Feed category**
- **Individual chicken identifier**

Each chicken is observed repeatedly over time, enabling both individual and group-level growth analysis.


---

## Analysis Workflow
The project follows a structured EDA approach:

1. **Data loading and inspection**
   - Overview of structure, data types, and basic statistics
2. **Descriptive statistics**
   - Mean, median, distribution spread, and outlier detection
3. **Growth analysis over time**
   - Weight development by age
   - Individual growth trajectories
4. **Feed category comparison**
   - Grouped line plots
   - Faceted visualizations by feed type
5. **Correlation analysis**
   - Relationships between age, weight, and feed
6. **Age group segmentation**
   - Comparison of weight distributions across life stages

---

## Key Insights (Summary)
- Chicken weight strongly correlates with age, showing consistent growth over time.
- Feed categories influence weight development, especially in later life stages.
- Some feed groups show more stable and uniform growth patterns than others.
- Individual-level analysis reveals outliers that may indicate health issues or exceptional growth.
- Correlation between feed category and weight appears low numerically, highlighting the limitation of correlation metrics for categorical variables.

A detailed interpretation of all findings is provided directly in the notebook.

---

## 🛠 Tools & Technologies
- Python  
- pandas  
- matplotlib  
- seaborn  
- Jupyter Notebook  


---

## How to Use
1. Open the notebook in the `notebooks/` folder
2. Run the cells top to bottom to reproduce the analysis
3. Review visualizations and interpretations embedded in the notebook

---

## Notes
This project focuses on **exploratory analysis and interpretability**, not predictive modeling.  
It demonstrates how data visualization and structured EDA can generate action
