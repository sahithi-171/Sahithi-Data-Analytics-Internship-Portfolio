Netflix Content Analytics Dashboard
-------------------------------------
Project Overview
----------------
This project performs an end-to-end analysis of the Netflix Titles Dataset using Python, SQL, and Power BI. The objective is to clean and transform the dataset, perform exploratory data analysis (EDA), answer business questions, and build an interactive Business Intelligence dashboard to uncover meaningful insights about Netflix's content library.


Dataset
--------
**Dataset:** Netflix Titles Dataset

The dataset contains information about Netflix movies and TV shows, including:

* Title
* Type (Movie / TV Show)
* Director
* Cast
* Country
* Date Added
* Release Year
* Rating
* Duration
* Genre

---

Project Workflow
-----------------
1. Data Cleaning & Wrangling
----------------------------
Performed using Python (Pandas).

Tasks completed:

* Removed duplicates
* Handled missing values
* Standardized column formats
* Converted data types
* Created `duration_numeric` for analysis
* Prepared a clean dataset for reporting

Output:

* `cleaned_netflix_data.csv`


2. Exploratory Data Analysis (EDA)
----------------------------------
Performed analysis to identify patterns and trends in Netflix content.

Key areas analyzed:

* Content growth over time
* Movies vs TV Shows distribution
* Country-wise content production
* Content ratings distribution
* Duration analysis
* Release year trends


3. SQL Business Analysis
-------------------------
Business questions explored using SQL:

* How many titles are available on Netflix?
* Which countries produce the most content?
* What are the most common content ratings?
* How has content production changed over time?
* What is the distribution of Movies and TV Shows?


4. Business Intelligence Dashboard
----------------------------------
An interactive Power BI dashboard was developed to visualize key metrics and insights.

Dashboard Components:
---------------------
KPIs
-----
* Total Titles
* Total Movies
* Total TV Shows
* Total Countries
* Latest Release Year

Visualizations
--------------
* Netflix Content Growth Over Time
* Movies vs TV Shows Distribution
* Content Distribution by Rating
* Top 10 Content Producing Countries
* Content Duration Distribution

Interactive Filters
-------------------
* Type
* Country
* Rating
* Release Year


Tools & Technologies
--------------------
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SQL
* Power BI
* Jupyter Notebook


Key Insights
------------
* Movies dominate Netflix's content catalog.
* Netflix content production increased significantly after 2015.
* The United States contributes the highest number of titles.
* TV-MA and TV-14 are among the most common content ratings.
* Netflix offers a diverse range of content durations and genres.


Project Files
-------------
* `netflix_titles.csv` – Original Dataset
* `cleaned_netflix_data.csv` – Cleaned Dataset
* `deep_dive_analysis.ipynb` – Data Analysis Notebook
* `Netflix titles dashboard.pbix` – Power BI Dashboard
* `SQL QUERIES.docx` – SQL Analysis
* `dashboard.pptx` – Project Presentation
* `data_dictionary.xlsx` – Data Dictionary

Conclusion
----------
This project demonstrates the complete data analytics workflow, from data cleaning and exploratory analysis to business intelligence reporting and dashboard development. The dashboard enables users to explore Netflix content interactively and derive meaningful business insights from the dataset.
