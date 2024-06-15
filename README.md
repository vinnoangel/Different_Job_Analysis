# Introduction

In today's dynamic job market, understanding the landscape of job postings and employer demands is crucial for both job seekers and organizations looking to recruit top talent. This report delves into an analysis of a comprehensive database encompassing various facets of job postings and company profiles. The database includes data from five primary tables: `company_dim`, `skills_dim`, `skills_job_dim`, `job_postings_fact`, and `job_applied`, providing insights into the relationships between companies, job postings, required skills, and applicant profiles.

Through exploratory data analysis and visualization techniques, this report aims to uncover meaningful patterns and trends, answering key questions such as the total number of companies represented, the most in-demand skills sought by employers, and insights into salary trends and job types. By examining these factors, stakeholders can gain actionable insights to better navigate the competitive job market and make informed decisions regarding recruitment strategies and career development.

The analysis utilizes SQL queries for data extraction and manipulation, combined with Python libraries such as pandas, psycopg2, and matplotlib for data processing and visualization. Each section of this report provides a detailed examination of specific metrics and trends, offering a comprehensive view of the current job landscape based on the provided dataset.

🔍 SQL queries? Check them out here: [project_sql folder](/project_sql/)


### The questions I wanted to answer through this prject were:

1. How many companies are there in total?
2. How many companies with less than 50 jobs compared with companies with more than 50 jobs?
3. Which companies have the highest number of job postings?
4. Find top 10 job titles with the highest job postings
5. What are the most in-demand skills based on job postings?, etc

# Tools I Used
For my deep dive into the data analyst job market, I harnessed the power of several key tools:

- **SQL:** The backbone of my analysis, allowing me to query the database and unearth critical insights.
- **PostgreSQL:** The chosen database management system, ideal for handling the job posting data.
- **Visual Studio Code:** My go-to for database management and executing SQL queries.
- **Git & GitHub:** Essential for version control and sharing my SQL scripts and analysis, ensuring collaboration and project 

The tools and technologies used in this analysis are as follows:

1. **Database Management System (DBMS)**:
   - **PostgreSQL**: The relational database system used to store and manage the data.

2. **Python Libraries**:
   - **Pandas**: For data manipulation and analysis.
   - **SQLAlchemy**: For creating database connections and executing SQL queries.
   - **psycopg2**: PostgreSQL adapter for Python, used to connect to the PostgreSQL database.
   - **Matplotlib**: For creating static, animated, and interactive visualizations in Python.
   - **Seaborn**: A statistical data visualization library based on Matplotlib, providing a high-level interface for drawing attractive and informative statistical graphics.
   - **dotenv**: For managing environment variables securely.

3. **Development Environment**:
   - **Jupyter Notebook**: For interactive coding and visualization, facilitating the exploration and presentation of data.

4. **SQL Queries**: Used for data extraction and manipulation directly from the PostgreSQL database.

These tools collectively enabled the extraction, processing, and visualization of data, allowing for comprehensive analysis and insightful visual representations of the job market trends and company profiles.


# Data Extraction and Preparation

The dataset comprises five primary tables: `company`, `skills`, `skills_job`, `job_postings`, and `jobs_applied`, which collectively provide a detailed view of the job market dynamics. SQL queries were employed to extract and aggregate data, while Python libraries such as Pandas facilitated data manipulation and preparation for analysis.

# Analysis Findings

1. **Total Companies and Job Postings:**
   - The database includes a total of 140,033 companies represented.
   - There are 787,686 job postings recorded in the dataset.

2. **Top Companies by Job Postings:**
   - Companies like Emprego, Booz Allen Hamilton, and Dice lead with the highest number of job postings, showcasing diverse roles and opportunities.

3. **Most In-Demand Skills:**
   - Skills such as SQL, Python, AWS, and Excel emerge as the most sought-after across job titles and industries.
   - Visualization tools like Matplotlib and Seaborn were used to illustrate these insights through bar charts and pie charts.

4. **Salary Trends and Job Types:**
   - Analysis of salary data revealed competitive salary ranges across different job roles and locations.
   - Insights into job types (full-time, part-time, remote) provided a comprehensive view of employment opportunities.


# What I Learned

Through this analysis, several key insights and learnings have been gleaned from the dataset:

1. **Data Retrieval and Management**:
   - Utilizing SQL queries to extract and aggregate data from a PostgreSQL database.
   - Employing Python libraries like Pandas and SQLAlchemy for efficient data manipulation and management.

2. **Exploratory Data Analysis (EDA)**:
   - Conducting exploratory data analysis to uncover patterns, trends, and relationships within the dataset.
   - Understanding the distribution of job postings across companies, job titles, and industries.

3. **Visualization Techniques**:
   - Using Matplotlib and Seaborn to create insightful visualizations such as bar charts, pie charts, and histograms.
   - Visualizing data to effectively communicate findings and trends to stakeholders.

4. **Skills and Tools in Demand**:
   - Identifying the most in-demand skills across different job titles and industries.
   - Recognizing the importance of skills such as SQL, Python, Tableau, and Excel in today's job market.

5. **Company Insights**:
   - Analyzing the top companies with the highest number of job postings and their respective job categories.
   - Gaining insights into salary trends and job types offered by leading employers.

6. **Report Writing and Communication**:
   - Structuring and presenting findings in a clear and organized manner suitable for stakeholders.
   - Communicating insights effectively through written reports and visualizations.

7. **Continuous Learning and Improvement**:
   - Emphasizing the importance of continuous learning and adaptation in data analysis and visualization techniques.
   - Iteratively refining analysis methods to derive deeper insights and provide actionable recommendations.


# Conclusion

The analysis underscores the critical role of data analytics in understanding market trends, informing recruitment strategies, and guiding career decisions. By leveraging SQL for data retrieval and Python for analysis and visualization, this report offers actionable insights for stakeholders navigating the dynamic job market landscape.

# Recommendations

1. **Skill Development
   - Job seekers are encouraged to focus on enhancing skills in SQL, Python, cloud computing, and data analysis tools to remain competitive.
   
2. **Recruitment Strategies
   - Employers can leverage insights into top companies and skill demands to refine recruitment strategies and attract top talent.
   
3. **Market Monitoring
   - Continuous monitoring of job market trends and adaptation to emerging skills and technologies is recommended for sustained competitiveness.

# Future Directions

Future analysis could include deeper dives into specific job tiles or geographical regions, as well as incorporating machine learning techniques for predictive analytics in job market trends.

# Appendix

Detailed SQL queries and Python code used for data extraction and analysis are provided for reference and replication of the analysis.

This report serves as a foundational tool for stakeholders looking to leverage data-driven insights in navigating and succeeding in the contemporary job market landscape.