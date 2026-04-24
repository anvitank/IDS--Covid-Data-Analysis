**Experiment 19 & 20**

**Name: Anvi Singh Tank**

**PRN: 25070123019**

**Batch: ENTC A1**

**Title**

**Project Analysis: COVID-19 Global Data Analysis and Visualization**

**Aim**

To perform a comprehensive end-to-end data analysis project on a real-world COVID-19 dataset, encompassing data cleaning, wrangling, statistical summarization, and advanced visualization.

**Objectives**

- To load and explore a large-scale global health dataset.
- To perform data wrangling and handle missing values in a time-series context.
- To calculate key pandemic metrics such as total cases, deaths, and recovery rates.
- To visualize the progression of the pandemic using line plots, bar charts, and pie charts.
- To derive geographical insights into the impact of the virus across different regions.

**Theory on Project Data Analysis**

A complete data analysis project integrates all previously studied Python techniques into a single pipeline. For a project like COVID-19 Analysis, the process follows these standard stages:

1. Data Ingestion and Inspection

The process begins by loading the dataset (CSV format) using Pandas. Initial exploration involves checking df.shape, df.info(), and df.head() to understand the granularity of the data (e.g., daily reports vs. cumulative totals).

2. Data Wrangling and Cleaning

Real-world health data often contains inconsistencies. Data wrangling here includes:

Handling Missing Values: Filling null values in "Recovered" or "Deaths" columns.

Date Transformation: Converting date strings into Python datetime objects to allow for chronological sorting and time-series plotting.

Formatting: Standardizing country names and removing redundant columns.

3. Exploratory Data Analysis (EDA)

EDA involves using statistical functions to summarize the pandemic's impact. Key operations include grouping data by "Country/Region" or "Date" and calculating aggregates like .sum() and .max() to find the most affected areas or peak infection dates.

Project Implementation Highlights
Based on the provided notebook, the following specific analytical tasks were executed:

Data Summary and Aggregation

The code groups the global data to provide a "Snapshot" of the pandemic. It calculates the total number of confirmed cases, deaths, and recovered cases globally and per country.

Trend Visualization

Growth Curves: Line plots were utilized to show the exponential growth of confirmed cases over time.

Impact Comparison: Bar charts were generated to compare the top 10 most affected countries based on total deaths and cases.

Proportional Analysis: Pie charts were used to visualize the ratio of Deaths vs. Recovered vs. Active cases within the total confirmed count.

Specialized Metrics

The analysis likely included the calculation of the Mortality Rate (Deaths / Confirmed) and Recovery Rate (Recovered / Confirmed) to assess the severity of the pandemic in different regions.

**Applications of Pandemic Data Analysis**

Public Health Policy: Informing government decisions on lockdowns and resource allocation.

Resource Management: Tracking the demand for hospital beds and medical supplies based on active case counts.

Predictive Modeling: Using historical trends to forecast future waves of infection.

Communication: Providing the general public with clear, visual representations of health risks.

**Conclusion**

Experiments 19 and 20 demonstrate the power of Python as a tool for real-world problem-solving. By combining Pandas for data manipulation and Matplotlib/Seaborn for visualization, we transformed a massive raw dataset of COVID-19 records into a series of insightful trends and comparisons. This project highlights the importance of data cleaning and structured visualization in understanding global crises and making data-driven decisions.
