# Netflix Engagement Analytics with Power BI Dashboard  

This project analyzes **Netflix’s global engagement data (Jan–Jun 2023)** to uncover patterns in viewing behavior and generate actionable insights through **data cleaning, analysis, and interactive dashboarding**.


## Problem Statement  
Netflix wants to understand:  
-  **Which titles drive the most engagement?**  
-  **Does global availability affect viewing hours?**  
-  **How do viewing trends evolve over time?**  

This project answers these questions by analyzing the dataset and visualizing the results with Power BI.

## Dataset  
The dataset contains **18,214 entries** with the following key fields:  
- `Title` → Name of the show or movie  
- `Available Globally` → Whether the content is available worldwide  
- `Release Date` → Date of release (many missing values)  
- `Hours Viewed` → Total viewing hours  

Data cleaning handled missing dates and formatted columns for time-series analysis.

## Tools Used  
- **Python (Pandas, NumPy, Matplotlib)** → for cleaning and preprocessing  
- **Power BI** → for creating interactive dashboards  
- **Jupyter Notebook** → for initial exploration  

## Files Included  

| **File**                           | **Description**                                    |
|-----------------------------------|--------------------------------------------------|
| `01_eda_netflix.ipynb`            | Exploratory Data Analysis in Python              |
| `netflix_engagement_clean.csv`    | Cleaned dataset used for analysis                |
| `global_vs_nonglobal.csv`         | Processed data comparing global vs non-global titles |
| `monthly_views.csv`               | Aggregated monthly viewing hours data            |
| `top10_titles.csv`                | Top 10 most-watched titles                       |
| `Netflix_Engagement_Dashboard.pbix`| Power BI dashboard (interactive)                 |
| `Netflix_Engagement_Dashboard.pdf`| Static dashboard report                          |



## Dashboard Highlights  
The Power BI dashboard includes:  
-  **Top 10 titles** by hours viewed  
-  **Global vs Non-Global content share**  
-  **Trend of viewing hours over years**  
-  **KPIs:** Total Hours Viewed & % of Global Titles  


## Author  
**Khushboo Masih**  
*MSc Data Science | Bachelor's in Business Administration*  
[khushboomashih193@gmail.com](mailto:khushboomashih193@gmail.com)  
[LinkedIn](https://www.linkedin.com/in/khushboo-masih/)


## License  
This project is for educational purposes and showcases analytics & visualization capabilities.
