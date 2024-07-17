# BankProduct_Strategy Data Analysis

### Table of Contents

- [Project Objective](#project-objective)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Processing](#data-processing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Visualization](#data-visualization)
- [Findings](#findings)
- [Recommendations](#recommendations)
- [References](#references)

### Project Objective 

Mitron Bank is a legacy financial institution headquartered in Hyderabad. They want to introduce a new line of credit cards to broaden their product offerings and reach in the financial market.

AtliQ Data Services learned about this through an internal link and approached Mitron Bank with a proposal to implement this project. However, the strategy director of Mitron Bank, Mr.Bashnir Rover is skeptical and asked them to do a pilot project with the sample data before handing them the full project. They provided a sample dataset of 4000 customers across five cities on their online spending and other details.

You are a data analyst at AtliQ Data Services and were asked by your manager Tony Sharma to take over this project. Your role is to analyze the provided sample data and report key findings to the strategy team of Mitron Bank. This analysis is expected to guide them in tailoring the credit cards to customer needs and market trends.

The successful acquisition of this project depends on your ability to provide actionable, data-driven recommendations and impress Mr. Bashnir Rover & his team. 

Your manager Tony Sharma, has provided some ideas to generate insights based on the data provided. your objectives as a data analyst are:-
1. Use “Insight Ideas from Tony.pdf”. Create metrics and visuals accordingly.
2. Design a dashboard with your metrics and analysis. The end users of this dashboard are top-level management and the product strategy team - hence the dashboard should be self-explanatory and easy to understand.

### Data Sources

The primary dataset used for this analysis is "dim_customers.csv" and "fact_spends.csv". These datasets will be utilized to uncover business opportunities, generate insights, and propose data-driven actions to optimize campaign results and create value for the company.

### Tools Used

- Jupyter Notebook (Python)
- Tableau for data visualization

### Data Processing

#### Data Import:

The "dim_customers.csv" and "fact_spends.csv" datasets were imported into Python using Jupyter Notebook.

#### Data Cleaning and Preparation: 

- Checking for Duplicates
- Confirming no null values in the dataset
- Standardizing Data types
- Joining or merging datasets 

#### Exploratory Data Analysis

- The Key Metric in this case is Average income utilization % of customers = (avg_spends/avg_income).
- To classify the customers based on available demography such as age group, gender, occupation, etc., and provide insights based on them.
- Providing Spending insights to the Product Strategy Team in the Banking Domain.
- Propose and describe Key Customer Segmentation based on customer behaviors.
- Provide Credit Card Feature recommendations to improve the likelihood of credit card usage.

### Data Visualization

After EDA, the cleaned dataset was exported to Tableau for advanced data visualization, providing a more intuitive understanding of customer segmentations and spending insights. The visualization can be accessed through the [Tableau Dashboard](https://public.tableau.com/views/CreditCardSalesInsight/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).
  
### Findings

The average income utilization percentage of the sample is 42.82%, indicating that approximately 40-50% of the sample is more likely to use a credit card.

#### 1. Age Group:
- The age group 35-45 has the highest average income utilization, followed closely by the 25-34 age group. Both these groups also exhibit the highest spending levels.
- Although the 45+ age group has the highest average income, their spending is lower compared to the other cohorts.
- The 21-24 age group has the lowest income range and spends the least among all age cohorts.

![1](https://github.com/user-attachments/assets/d30aea9e-33fd-4490-843b-b0c486e4e0da)


![3](https://github.com/user-attachments/assets/9deaa329-f037-437c-a96f-b3ae31abd797)

#### 2. City:
- Mumbai and Delhi NCR have the highest spending variability, with Mumbai showing the highest overall spending.
- A positive correlation between income and spending is evident across all cities, with Mumbai, Delhi, and Bengaluru displaying notable clusters of high-income, high-spending individuals.
- Hyderabad's spending patterns are moderate, with less extreme spending behavior compared to other cities.
- Chennai exhibits the lowest median spending, indicating more conservative financial behavior.

![4](https://github.com/user-attachments/assets/b728339f-6e79-48b6-b0aa-5b04cc2d8d8a)


![5](https://github.com/user-attachments/assets/1e593d58-005a-4b14-a58c-23dc63471818)

#### 3. Occupation:
- Salaried IT employees exhibit the highest spending variability, with many spending significantly more than other groups.
- Business owners also show high spending levels similar to IT employees but with less variability.
- Salaried IT employees have the highest income utilization percentage at 51%, along with the most high-income and high-spending cluster.
- Freelancers have the lowest income and spending values but the second-highest average income utilization percentage.
- Business owners, despite having the highest average income cluster, display relatively low spending, resulting in one of the lowest average income utilization percentages at 33%.

![6](https://github.com/user-attachments/assets/6a2398cb-b882-4c4a-9015-a294a47b8c55)


![7](https://github.com/user-attachments/assets/d3e879fa-b1f8-4a77-abbb-574a5cf31d78)

#### 4. Gender:
- Males have higher average monthly spending compared to females.
- Despite the average income range for females being as broad as that for males, their spending is lower.
- The average income utilization percentage for men is 5% higher than that for women.

![8](https://github.com/user-attachments/assets/a5eec068-7d68-4532-840f-81fac2f138a9)


![9](https://github.com/user-attachments/assets/01bb7065-fb78-4de8-a0eb-4ac7aeb5d151)

#### 5. Marital Status:
- Married customers exhibit higher spending variability compared to single customers.
- The scatterplot for average income versus average spending is similar for both married and single customers, and the average income utilization percentage is the same for both groups.
- The dataset includes nearly 3,100 married individuals and 860 single individuals; a more balanced dataset might provide deeper insights, especially for the higher average income range.

![10](https://github.com/user-attachments/assets/6ddc1832-0f9d-4240-b124-839ab0225e63)


![11](https://github.com/user-attachments/assets/761a5e1b-4790-4bf4-9945-4af4c65963b1)

#### 6. Preferred Payment type:
- Credit cards are the most preferred payment method for spending, followed by UPI.
- Among age groups, those aged 45+ and 35-45 prefer credit cards first and debit cards second.
- The 25-34 age group also prefers credit cards, followed by UPI.
- The 21-24 age group prefers UPI first and credit cards second.
- The highest average spending with credit cards is observed in the 25-34 and 35-45 age groups. 

![12](https://github.com/user-attachments/assets/d3d081f6-c22f-4716-b1a3-170e8aab8873)


![13](https://github.com/user-attachments/assets/4908219d-0aa7-4148-9a5e-cdc0e79572f3)

#### 7. Category:
- Overall, customers spend the most on bills, followed by groceries.
- Men prioritize bills, groceries, and electronics, while women spend the most on health and wellness, followed by bills and travel.
- Individuals aged 21-24 spend the most on entertainment.
- Both the 25-34 and 35-45 age groups spend the most on bills and groceries. The next highest spending category for the 35-45 age group is health and wellness, while for the 25-34 age group, it is electronics.
- Married individuals allocate most of their spending to bills, groceries, electronics, and health and wellness.
- Single individuals prioritize spending on electronics, bills, entertainment, and groceries.
- The top five categories of spending—bills, groceries, electronics, health and wellness, and travel—are predominantly paid for using credit cards. The only significant competition between credit cards and UPI is observed in the groceries category.


![15](https://github.com/user-attachments/assets/d8365f01-8e8d-4fbc-bcba-adc3b1d6f845)

![16](https://github.com/user-attachments/assets/d6a5f663-6ddf-482f-bf71-31bf1d6280b4)

![18](https://github.com/user-attachments/assets/063015bd-f756-48fb-9513-1482658fabcc)

![19](https://github.com/user-attachments/assets/2a165b15-0c36-4d98-821c-6e10a8a111e5)

![20](https://github.com/user-attachments/assets/f8060b01-fd54-47cd-99f4-92b9ca3964ff)

### Recommendations
#### 1. Age Group: 
Tailor credit card features for the 35-45 and 25-34 age groups with rewards on bills, groceries, and electronics. For the 21-24 age group, offer benefits on entertainment and UPI compatibility.

#### 2. City:
Launch targeted marketing campaigns in Mumbai, Delhi NCR, and Bengaluru to attract high-income, high-spending customers. For Hyderabad and Chennai, offer conservative financial products with moderate rewards.

#### 3. Occupation:
Develop premium credit cards for salaried IT employees and business owners, offering high rewards on technology and business-related expenses. For freelancers, offer flexible credit options with moderate rewards.

#### 4. Gender:
Develop customized reward programs for different spending categories to cater to both genders. Offer higher rewards on bills and groceries and specific benefits for electronics (men) and health and wellness (women).

#### 5. Marital Status:
Offer family-oriented credit card benefits for married customers, such as rewards on groceries, health and wellness, and bills. For single customers, emphasize rewards on electronics and entertainment.

  
### References

1.  [Code Basics](https://codebasics.io/challenge/codebasics-resume-project-challenge)
