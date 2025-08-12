# Data Science Internship at SkillCraft Technology  
__________
## Task 3 – Exploratory Data Analysis on Online Shoppers Intention Dataset
________

## Overview
This project is part of Task 3 of my Data Science Internship at SkillCraft Technology.  
The goal was to perform data cleaning, outlier handling, and exploratory data analysis (EDA) on the **Online Shoppers Intention** dataset to identify behavioral patterns that influence purchasing decisions.

---

## Dataset Description
The dataset contains session-level information of online shoppers with the following key columns:

- **Administrative / Administrative_Duration** – Pages & time spent on administrative sections.  
- **Informational / Informational_Duration** – Pages & time spent on informational sections.  
- **ProductRelated / ProductRelated_Duration** – Pages & time spent on product-related sections.  
- **BounceRates, ExitRates** – Session abandonment and exit metrics.  
- **PageValues** – Estimated value of a page in terms of conversion.  
- **SpecialDay** – Proximity to a special day (e.g., Valentine's Day).  
- **OperatingSystems, Browser, Region, TrafficType** – Technical and regional visitor information.  
- **VisitorType** – New or returning visitor.  
- **Weekend** – Whether the session occurred on a weekend.  
- **Revenue** – Target variable indicating if a purchase was made.

---

## Tools & Libraries Used
- **Pandas** – Data cleaning & manipulation  
- **NumPy** – Numerical computations  
- **Matplotlib** – Visualization  
- **Seaborn** – Statistical plots  
- **Jupyter Notebook** – Interactive analysis  

---

## Data Cleaning Process
1. **Handled Missing Values** – Checked for and addressed missing entries.  
2. **Removed Duplicates** – Eliminated repeated session records.  
3. **Outlier Treatment** – Applied **IQR method** to detect and cap extreme values in numerical columns.  
4. **Skewness Handling** – Considered transformation for highly skewed features.  
5. **Encoding** –  
   - Binary encoding for Boolean features (`Weekend`)  
   - One-hot encoding for categorical features (`VisitorType`, `Month`, etc.)  

---

## Exploratory Data Analysis (EDA)
The following analyses were conducted:
- Distribution of numerical features before & after outlier treatment.  
- Boxplots for detecting outliers in behavioral metrics.  
- Correlation heatmap to identify strong relationships between features.  
- Session behavior patterns based on visitor type, month, and weekend.  
- Relationship between bounce/exit rates and revenue.  
- High-value pages’ influence on purchase decision.  

**Visualizations created include:**
- Histograms for feature distributions  
- Boxplots for outlier inspection  
- Count plots for categorical analysis  
- Heatmaps for feature correlation  
- Bar charts for revenue by visitor type, month, and weekend  

---

## Key Insights
- **Product Engagement** – Visitors spending more time on `ProductRelated` pages have higher purchase rates.  
- **Bounce & Exit Rates** – Negatively correlated with purchases.  
- **Page Values** – Strong positive indicator of purchase intention.  
- **Special Days** – Proximity to special days slightly increases purchases.  
- **Returning Visitors** – More likely to make a purchase than new visitors.  

---

## Conclusion
This task revealed key behavioral indicators that can help optimize e-commerce websites.  
Findings can guide marketing, UX improvements, and targeted campaigns to increase conversions.

---

## 🙏 Acknowledgement
Thank you for reviewing my submission for **Task 3** of the SkillCraft Technology Data Science Internship.
