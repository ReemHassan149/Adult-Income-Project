# Adult-Income-Project
This report provides a professional summary and analysis based on a standard "Adult Income" dataset, typically used to predict whether an individual earns more or less than $50,000 annually based on socio-economic factors.

# Executive Summary
This dashboard analyzes the relationship between demographic characteristics (Age, Sex, Race) and professional attributes (Education, Occupation, Work Class) to identify key drivers of high income. The primary goal is to provide stakeholders with actionable insights into workforce trends and economic disparities.
- Python script for cleaning  http://localhost:8888/notebooks/Untitled10.ipynb
- ### Raw Data [adult.csv](https://github.com/user-attachments/files/24371796/adult.csv)
- ### Cleaned Data [adult_cleaned.csv](https://github.com/user-attachments/files/24371824/adult_cleaned.csv)

- DashBoard
![Education](https://github.com/user-attachments/assets/5ae8a5e5-7e7d-4fc7-8d3a-0b3944f6dac8)
![Sex](https://github.com/user-attachments/assets/624d21aa-ab36-4ce0-a26d-38e3286bf7b5)
![Occupation](https://github.com/user-attachments/assets/86696dcb-cfa6-4d61-a0ea-86bdde95d0b1)
![Age](https://github.com/user-attachments/assets/b5258708-9e4a-48ff-8e54-0f28a99a2920)
![Country](https://github.com/user-attachments/assets/e2882cd4-cf62-406a-8be5-c8cc855402b6)
![Marital Status](https://github.com/user-attachments/assets/afe36e05-628a-4ae0-847e-db4364711b71)
![Relationship](https://github.com/user-attachments/assets/32f2f94a-6d09-44ff-932f-12a53d67bb29)
![Work Class](https://github.com/user-attachments/assets/ac8573c9-36ea-423a-88ff-fb622edb3145)
![Race](https://github.com/user-attachments/assets/34181105-69c2-44e5-84d7-4504d22dc0b7)
![Star Schema ](https://github.com/user-attachments/assets/8115038f-2753-4eea-9087-b039c03095fb)



## 1. Demographic Overview
Understanding the baseline population is critical for contextualizing income trends.

- **Age Distribution**: Analysis shows how income typically **peaks** during mid-career **(ages 35–50)** before stabilizing.

- **Gender Gap**: Examining the distribution of high earners (>50k) often reveals significant disparities between male and female demographics.

- **Marital Status & Relationship**: Data frequently indicates that **"Married-civ-spouse"** individuals represent a **higher** proportion of the high-income bracket compared to single or divorced counterparts.

## 2. Professional Drivers of Income
This section highlights which career choices most impact financial status.

- **Education Level**: There is a direct, positive correlation between**advanced degrees** (Bachelors, Masters, Prof-school) and the likelihood of **exceeding** the $50k threshold.

- **Occupation Highlights**: Roles such as **"Exec-managerial"** and **"Prof-specialty"** consistently show the highest concentration of high earners.

- **Work Class**: **Private** sector employees form the **bulk** of the dataset, while **"Self-emp-inc"** (incorporated self-employed) often has a high percentage of **top-tier earners**.

## 3. Key Insights & Trends
- **The "Education Ceiling"**: Individuals **without** at least some college education have a statistically **lower** probability of entering the high-income bracket, **regardless** of work hours.

- **Productivity vs. Pay**: Analysis of "Hours-per-week" against income suggests that while **40** hours is **standard**, **high earners** often report **45–50+** hours.

- **Geographic Concentration**: Mapping by "Native Country" helps identify if specific immigrant or native groups face unique economic barriers or advantages.

## 4. Strategic Recommendations
Based on the data, the following actions are recommended to address income inequality or improve workforce planning:

- **Skill Development**: Invest in targeted vocational training for occupations with high growth but low current high-earner density.

- **Educational Accessibility**: Programs aimed at increasing college completion rates directly influence the long-term economic status of the population.

- **Equity Initiatives**: Address the observed gender and race disparities in high-paying managerial roles through inclusive hiring practices.

## 5. Technical Methodology
**- Data Cleaning**: Handled missing values (often found in "Occupation" and "Work Class" columns) through mode imputation or exclusion and making star schema By using this Star Schema:

- **Speed**: Your "Slicer Panel" and dropdowns will respond instantly because the engine only has to filter small dimension tables.

- **Accuracy**: It prevents "double-counting" of data that can happen in flattened (single-table) datasets.

- **Scalability**: If you wanted to add new data (like income data from a different year), you could easily plug it into the existing dimensions..

**- Visual Design**: Used Slicer Panels for demographics to maximize space for core KPIs like "Total High Earners" and "Average Hours Worked".

### Raw Data [adult.csv](https://github.com/user-attachments/files/24371796/adult.csv)
### Cleaned Data [adult_cleaned.csv](https://github.com/user-attachments/files/24371824/adult_cleaned.csv)

