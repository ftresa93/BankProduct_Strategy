# BankProduct_Strategy Data Analysis

### Table of Contents

- [Project Objective](#project-objective)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Visualization](#data-visualization)
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

### Data Visualization:

After EDA, the cleaned dataset was exported to Tableau for advanced data visualization, providing a more intuitive understanding of customer segmentations and spending insights. The visualization can be accessed through the [Tableau Dashboard](https://public.tableau.com/views/CreditCardSalesInsight/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).
  
### Findings:

The average income utilization percentage of the sample is 42.82%, indicating that approximately 40-50% of the sample is more likely to use a credit card.

#### 1. Age Group-
The age group 35-45 has the highest average income utilization, followed closely by the 25-34 age group. Both these groups also exhibit the highest spending levels. Although the 45+ age group has the highest average income, their spending is lower compared to the other cohorts. The 21-24 age group has the lowest income range and spends the least among all age cohorts.

![1](https://github.com/user-attachments/assets/d30aea9e-33fd-4490-843b-b0c486e4e0da)


![3](https://github.com/user-attachments/assets/9deaa329-f037-437c-a96f-b3ae31abd797)

#### 2. City-
The analysis reveals that Mumbai and Delhi NCR have the highest spending variability, with Mumbai showing the highest overall spending. A positive correlation between income and spending is evident across all cities, with Mumbai, Delhi, and Bengaluru displaying notable clusters of high-income, high-spending individuals. Hyderabad's spending patterns are moderate, with less extreme spending behavior compared to other cities. Chennai exhibits the lowest median spending, indicating more conservative financial behavior.

![4](https://github.com/user-attachments/assets/b728339f-6e79-48b6-b0aa-5b04cc2d8d8a)


![5](https://github.com/user-attachments/assets/1e593d58-005a-4b14-a58c-23dc63471818)

#### 3. Occupation-
Salaried IT Employees exhibit the highest spending variability, with many spending significantly more than other groups. Business Owners also show high spending levels similar to IT employees but with less variability. 
Salaried IT Employees have the highest income utilization percentage at 51%, along with the most high-income and high-spending cluster. Freelancers have the lowest income and spending values but the second-highest average income utilization percentage. Business Owners, despite having the highest average income cluster, display relatively low spending, resulting in one of the lowest average income utilization percentages at 33%.

![6](https://github.com/user-attachments/assets/6a2398cb-b882-4c4a-9015-a294a47b8c55)


![7](https://github.com/user-attachments/assets/d3e879fa-b1f8-4a77-abbb-574a5cf31d78)

#### 4. Gender-
Males have higher average monthly spending compared to females. Interestingly, despite the average income range for females being as broad as that for males, their spending is lower. Additionally, the average income utilization percentage for men is 5% higher than that for women.

![8](https://github.com/user-attachments/assets/a5eec068-7d68-4532-840f-81fac2f138a9)


![9](https://github.com/user-attachments/assets/01bb7065-fb78-4de8-a0eb-4ac7aeb5d151)

#### 5. Marital Status-
Married customers exhibit higher spending variability compared to single customers. The scatterplot for average income versus average spending is similar for both married and single customers. Additionally, the average income utilization percentage is the same for both groups.

![10](https://github.com/user-attachments/assets/6ddc1832-0f9d-4240-b124-839ab0225e63)


![11](https://github.com/user-attachments/assets/761a5e1b-4790-4bf4-9945-4af4c65963b1)

### Recommendations:
  
### References:

1.  [Code Basics](https://codebasics.io/challenge/codebasics-resume-project-challenge)
