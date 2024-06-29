# Pymaceuticals Analysis  

## OVERVIEW 

For this project we were tasked with conducting an analysis of pharmaceutical data to study the effects of various drug regimens on tumor volume in mice. This project further honed my Pandas data cleaning and summary statistics skills, which helped solidify my knowledge of Pandas functions - especially in a different data context. The project was my first foray into coding visualizations such as bar plots, pie charts, box plots, line plots, and scatter plots. It has prepared me to take my knowledge of analytical statistics, and create clear representations of different facets of the data through using Pandas, Matplotlib and Scipy. 

## Key Takeaways: 

The process of learning and applying Pandas data organization and charting through Matplotlib for this exercise, demonstrated the utility of the script. Some important benefits for stakeholders such as researchers, medical professionals and data analysts are as follows: 

**Treatment Efficacy:** Assess the effectiveness of different drug treatments based on tumor volume changes.

**Patient Insights:** Understand the relationship between factors such as mouse weight and tumor volume to make informed decisions about treatment plans.

**Drug Development:** Utilize the insights from statistical analysis and visualizations to improve drug development processes and make data-driven decisions.

**Risk Assessment:** Identify potential outliers and risks associated with specific treatment regimens.

**Trend Identification:** Detect trends and correlations in large datasets to provide actionable insights.

## Technologies and Skills Used

**Python:** Core programming language for data processing and analysis.

**Pandas:** Utilized for data cleaning, merging datasets, and conducting statistical computations.

**Matplotlib:** Used to generate a variety of plots and visual representations.

**Scipy:** Employed for advanced statistical analysis, including correlation, regression, and hypothesis testing.

## Code Logic 

**Data Loading and Preparation:**

Essential libraries like matplotlib.pyplot, pandas, and scipy.stats are imported.

File paths for mouse metadata and study results are defined.

Data from CSV files are loaded into Pandas DataFrames **(mouse_metadata and study_results)**.

DataFrames are merged based on "Mouse ID" to create a comprehensive DataFrame **(mousedata_combined).**

**Data Cleaning:**

The number of mice is checked for data consistency.

Duplicate entries based on **"Mouse ID"** and **"Timepoint"** are identified.

Duplicate rows are removed to ensure data accuracy.

**Summary Statistics:**

Summary statistics (mean, median, variance, standard deviation, and standard error of the mean) for tumor volume are computed, grouped by drug regimen.

A summary DataFrame is created to present these statistical measures.

**Bar and Pie Charts:**

Visual representations of the total observations **(Mouse ID/Timepoints)** for each drug regimen using both Pandas and Matplotlib are created.

Appropriate use of .index, .values to create x ticks and bar height.

Pie charts are generated to display the gender distribution of mice.

**Quartiles, Outliers, and Boxplots:**

The final tumor volume for each mouse under specific treatment regimens (Capomulin, Ramicane, Infubinol, and Ceftamin) is determined.

Quartiles, interquartile range (IQR), and potential outliers are calculated using looping and relevant formula.

Boxplots are utilized to visualize the spread of tumor volume across different treatment groups.

**Line and Scatter Plots:**

A line plot illustrates tumor volume changes over time for a single mouse treated with Capomulin.

A scatter plot demonstrates the relationship between mouse weight and average tumor volume for the Capomulin regimen.

**Correlation and Regression:**

The correlation coefficient between mouse weight and average tumor volume is calculated.

Linear regression analysis is performed to explore the association between mouse weight and tumor volume, with a regression line plotted.


