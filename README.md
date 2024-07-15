# BankProduct_Strategy Data Analysis

### Table of Contents

- [Project Objective](#project-objective)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Findings](#findings)
- [Recommendations](#recommendations)
- [References](#references)

### Project Objective: 

Mitron Bank is a legacy financial institution headquartered in Hyderabad. They want to introduce a new line of credit cards to broaden their product offerings and reach in the financial market.

AtliQ Data Services learned about this through an internal link and approached Mitron Bank with a proposal to implement this project. However, the strategy director of Mitron Bank, Mr.Bashnir Rover is skeptical and asked them to do a pilot project with the sample data before handing them the full project. They provided a sample dataset of 4000 customers across five cities on their online spending and other details.

You are a data analyst at AtliQ Data Services and were asked by your manager Tony Sharma to take over this project. Your role is to analyze the provided sample data and report key findings to the strategy team of Mitron Bank. This analysis is expected to guide them in tailoring the credit cards to customer needs and market trends.

The successful acquisition of this project depends on your ability to provide actionable, data-driven recommendations and impress Mr. Bashnir Rover & his team. 

Your manager Tony Sharma, has provided some ideas to generate insights based on the data provided. your objectives as a data analyst are:-
1. Use “Insight Ideas from Tony.pdf”. Create metrics and visuals accordingly.
2. Design a dashboard with your metrics and analysis. The end users of this dashboard are top-level management and the product strategy team - hence the dashboard should be self-explanatory and easy to understand.

### Data Sources:

The primary dataset used for this analysis is "dim_customers.csv" and "fact_spends.csv". These datasets will be utilized to uncover business opportunities, generate insights, and propose data-driven actions to optimize campaign results and create value for the company.

### Tools Used:

- Jupyter Notebook (Python) 

### Data Processing:

#### Data Import:

The "dim_customers.csv" and "fact_spends.csv" datasets were imported into Python using Jupyter Notebook.

#### Data Cleaning and Preparation: 

- Checking for Duplicates
- Confirming no null values in the dataset
- Standardizing Data types
- Joining or merging datasets 

#### Exploratory Data Analysis: 

- The Key Metric in this case is Average income utilization % of customers = (avg_spends/avg_income).
- To classify the customers based on available demography such as age group, gender, occupation, etc., and provide insights based on them.
- Providing Spending insights to the Product Strategy Team in the Banking Domain.
- Propose and describe Key Customer Segmentation based on customer behaviors.
- Provide Credit Card Feature recommendations to improve the likelihood of credit card usage.

#### Data Visualization:

After EDA, the cleaned dataset was exported to Tableau for advanced data visualization, providing a more intuitive understanding of customer segmentations and spending insights. The visualization can be accessed through the [Tableau Dashboard](https://public.tableau.com/views/CreditCardSalesInsight/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).
  
### Findings:




### Recommendations:


  
### References:

1.  [Code Basics](https://codebasics.io/challenge/codebasics-resume-project-challenge)
