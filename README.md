# Phase-2-project
![Alt text](<big data-1.jpg>)

## Moringa Phase 2 Project Submission

#### GROUP 4:

- Student name: Margaret Thiga
- Student name: Pete Njagi
- Student name: Jeremy Ngugi
- Student name: Esther Omulokoli
- Student name: James Koli
- Student name: Edgar Kiprono

# Data Science Jobs Anlysis Project

## Business Problem

KenyaData Insights, a cutting-edge data firm in Kenya, is set to launch with a distinctive aim to explore salary expectations among individuals aspiring to enter the realm of Data Science. Our investigation will span every tier of the organizational structure, from upper management to entry-level positions. Recognizing the pivotal role that compensation plays in job satisfaction, our startup is dedicated to examining how these expectations affect employee contentment and engagement. It is a priority for KenyaData Insights to develop a predictive model that analyzes and forecasts data science job salaries, considering factors such as job titles, experience levels, company size, and other pertinent variables to provide stakeholders with actionable insights for informed decision-making.

## Overview

The study's goal is to unpack the intricate relationships within the data and machine learning industry, specifically examining the interplay between job characteristics, compensation structures, and the dynamics of remote work. We aim to understand the variance in salaries against variables like employee residency, job titles, remote work ratios, and experience levels by creating visuals/graphs and employing statistical metrics like correlation coefficients. Additionally, the study sheds light on remote work patterns within the industry, investigating the impact of job titles and work experience on work-life balance and overall job satisfaction.

## Business Stakeholders

The primary stakeholders for this project include:

- Future data scientists
- Data science students
- Academic institutions
- Employers in the data science industry
- Career advisors
- Recruitment agencies

This project aims to provide insights for strategic salary determination and facilitate critical decision-making processes, thereby enhancing the work environment and contributing to business success.

## Business Objective

Our business objectives are:

- Developing a robust salary prediction model to understand factors influencing industry salaries.
- Optimising placement strategies for future data scientists.
- Improving recruitment processes with data-driven insights.
- Providing personalized guidance to optimise career advisory services.
- Establishing ethical data governance standards.
- Engaging with educational institutions and business partners for responsible data usage and alignment between education and industry demands.

The initiative aspires to deliver actionable data, support better personnel management, and foster career development within the industry.

## Hypotheses

i. **Hypothesis on Job Titles and Compensation:**
   - Null Hypothesis (H0): There is no significant difference in compensation across various job titles.
   - Alternative Hypothesis (H1): Compensation levels vary significantly based on different job titles.

ii. **Hypothesis on Work Experience and Salary:**
   - Null Hypothesis (H0): Work experience does not significantly impact salary levels.
   - Alternative Hypothesis (H1): Employees with more work experience command higher salaries.

iii. **Hypothesis on Regional Salary Disparities:**
   - Null Hypothesis (H0): There are no significant differences in salary distributions across various nations and regions.
   - Alternative Hypothesis (H1): Salary distributions vary significantly across different nations and regions.



### Data Understanding
The data sources for this analysis will be pulled from two separate files.

#### `data_sci_jobs.csv` (Main data source)
#### `ds_salaries.csv` 
* **Source**: This dataset comes from [`https://www.kaggle.com/datasets/georgejnr/advertised-data-science-jobs-dataset`](https://www.kaggle.com/datasets/georgejnr/advertised-data-science-jobs-dataset), a "free and open public domain data source"
* **Contents**: This dataset comprises data on data science information, vacancies in the united states and other countries advertised on Glassdoor's website. It contains information of the advertised company's name, the job title, estimated salary and the location of the job

#### Univariate Analysis
**Salaries in USD= unit of analysis**

**Unique identifiers:**
experience_level : 4
employment_type : 4
job_title : 50
salary_currency : 17
employee_residence : 57
remote_ratio : 3
company_location : 50
company_size : 3

## Regression Analysis

### Data Visualizations
<img src="/Images/NotebookExports/1.png" alt="drawing" width="500"/>

<img src="/Images/NotebookExports/2.png" alt="drawing" width="500"/>

<img src="/Images/NotebookExports/3.png" alt="drawing" width="500"/>

<img src="/Images/NotebookExports/4.png" alt="drawing" width="500"/>

<img src="/Images/NotebookExports/5.png" alt="drawing" width="500"/>

<img src="/Images/NotebookExports/6.png" alt="drawing" width="500"/>

<img src="/Images/NotebookExports/7.png" alt="drawing" width="500"/>

<img src="/Images/NotebookExports/8.png" alt="drawing" width="500"/>


## Setup for Jupyter Notebook

To set up a Jupyter Notebook for analyzing the data:

1. Install Anaconda which includes Jupyter Notebook, Python, and other data science packages. Visit [Anaconda's website](https://www.anaconda.com/products/distribution) and download the installer for your operating system.
2. After installation, launch Anaconda Navigator and start Jupyter Notebook, or open a terminal (or command prompt) and type `jupyter notebook` to start the Jupyter Notebook server.
3. Create a new Python notebook from the Jupyter dashboard.
4. Import the required libraries (e.g., pandas, matplotlib, seaborn, Statsmodels) at the beginning of your notebook.
5. Load your dataset using pandas, for example: `df = pd.read_csv('path_to_your_data.csv')`.
6. Proceed with your data analysis and visualization.

For more detailed instructions, you can refer to the [official Jupyter documentation](https://jupyter.readthedocs.io/en/latest/).


