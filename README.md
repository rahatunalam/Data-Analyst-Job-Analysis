This project explores a dataset of over 30,000 Data Analyst job postings collected via Google Search. 
The analysis focuses on salary trends, top hiring companies, in-demand skills, and the distribution of job types (Remote vs. On-site).

📊 Project Overview
The goal of this script is to uncover insights into the current job market for data analysts. It processes raw job posting data to answer questions like:
What are the most common skills requested by employers?
Which companies are hiring the most?
How do hourly pay rates compare to yearly salaries?
What percentage of jobs offer "Work from home" or "Health Insurance" benefits?

🛠️ Tech Stack
Language: Python 3.10+
Libraries:
pandas (Data manipulation)
numpy (Numerical operations)
matplotlib (Data visualization)

📁 Dataset
The analysis uses the Data Analyst Job Postings [Google Search] dataset by Luke Barousse.
Input File: gsearch_jobs.csv
Key Columns: salary_avg, description_tokens, company_name, via, extensions.

🚀 Key Features
Salary Analysis: Cleans and segments salary data into hourly and yearly brackets, providing descriptive statistics for each.
Skill Extraction: Parses the description_tokens column to identify the Top 20 most frequently mentioned technical skills.
Company & Platform Insights: Identifies the top 10 companies hiring and the primary job boards (sources) where listings are found.
Benefits & Job Types: Uses keyword extraction from the extensions field to visualize the prevalence of Remote work, Full-time status, and Insurance benefits.

📈 Visualizations Included
Bar Chart: Top 10 Companies by Job Postings.
Pie Chart: Distribution of Job Types (Full-time, Contractor, Internship, etc.).
