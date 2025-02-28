# Indian-Job-Market-Analysis
# 📊 Indian Job Market Analysis (2024) 🚀

## 🔍 Overview
This project analyzes the **Indian job market in 2024** using real-world job posting data. The analysis covers:
- Salary trends 💰
- Job demand across different cities & states 📍
- Industry insights & most common job roles 🏢

The dataset contains **835 job listings**, extracted from various sources.

---

## 📌 Key Insights
✔ **The job market is highly concentrated in metro cities.**  
✔ **Salary distribution is right-skewed, meaning a few jobs have very high salaries.**  
✔ **Certain job roles dominate the listings (e.g., Tech & Education).**  
✔ **Job availability varies widely by state and city.**  
✔ **Salaries vary significantly across job roles & locations.**  

---

## 📁 Dataset
The dataset is stored in `data/job_market_2024.csv` and contains the following columns:

| Column Name      | Description |
|-----------------|------------|
| Job Title       | Name of the job position |
| Location        | City & State of the job |
| Salary         | Salary range (raw text) |
| Monthly Salary | Extracted monthly salary |
| Locality       | Local area within the city |
| City          | City where the job is located |
| State         | State where the job is located |

📌 **Note:** The dataset contains **salary data in raw text format**, which was cleaned and analyzed.

---

## 🔧 Installation & Requirements
To run this analysis, you need **Python 3.x** and the following libraries:

```bash
pip install pandas numpy matplotlib seaborn
