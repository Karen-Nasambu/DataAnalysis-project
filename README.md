# DataAnalysis-project

Global Life Expectancy Analysis
 Goal

To understand what factors most influence life expectancy worldwide — such as GDP, education, healthcare spending, and immunization rates — and identify countries performing above or below expected levels.

Dataset

Source: WHO Life Expectancy Dataset (Kaggle)

Contains country-level data for:

Life expectancy

Adult mortality, infant deaths

Education (schooling years)

Health expenditure

GDP per capita

Immunization rates (Hepatitis B, Polio, Diphtheria)

Status (Developed vs Developing)

Year

Tools
Tool	Purpose
Microsoft Excel	Data cleaning, missing value handling, descriptive statistics
SQL (MySQL or SQLite)	Querying, filtering by region/year, joining external data
Tableau / Power BI	Building interactive dashboards, charts, and insights
(Optional) Power Query	For automated data transformations inside Excel
Process Overview

Data Cleaning (Excel or Power Query)

Remove duplicates and nulls

Standardize column names

Replace missing numeric values (like GDP, schooling) with averages

Strip spaces and format text fields (Country, Status)

Exploratory Data Analysis (Excel/SQL)

Compute average life expectancy by country and year

Find correlations between GDP, education, and life expectancy

Identify countries with above/below-average performance

Visualization (Tableau or Power BI)

Map view: Life expectancy by country

Scatter plot: GDP vs life expectancy

Line chart: Trend of life expectancy over time

Bar chart: Top and bottom performing countries

KPI cards: Global average, highest, lowest

Key Insights to Explore

Strong positive correlation between GDP, education, and life expectancy

Diminishing returns after a certain GDP level (wealth ≠ health)

Middle-income countries with strong immunization programs often outperform richer nations

Health spending efficiency varies widely — money isn’t the only factor

 Aha! Moments

“Some middle-income countries match or exceed life expectancy in richer nations — because of effective vaccination and preventive healthcare.”

“Beyond $30,000 GDP per capita, the increase in life expectancy flattens — suggesting better policy, not just income, drives longevity.”

“Countries with high education levels tend to achieve higher life expectancy even with moderate health spending.”

Dashboard Features

In Tableau or Power BI, include:

Global Map: Color-coded by life expectancy

GDP vs Life Expectancy Plot: With trendline

Top 10 Countries by Life Expectancy

Filters: Year, Status (Developed/Developing), Region

Insight Text Boxes: To highlight your key findings

Impact

For Policymakers: Identify which health or education factors yield the highest returns.

For NGOs: Focus funding where it has the biggest impact on longevity.

For Researchers: Benchmark health progress across nations.

Deliverables

Cleaned dataset (Excel or CSV)

Tableau/Power BI dashboard (.twbx or .pbix)

Project report or blog article (optional) — summarizing your findings and insights
