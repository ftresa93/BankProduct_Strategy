# BankProduct_Strategy Data Analysis

### Table of Contents

- [Project Objective](#project-objective)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Findings](#findings)
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

- Removing Duplicates
- Confirming no null values in the dataset
- Standardizing Data types

#### Exploratory Data Analysis: 

- Propose and describe customer segmentation based on customer behaviors.
- Visualize data to provide insights for improving customer engagement, which is key to growing and solidifying UFood’s position as the market leader.
 
### Findings:

#### 1. Age Group Spending and Campaign Acceptance:
   The age group of 31-70 exhibits the highest percentage of accepted campaigns and the highest amount spent, significantly outperforming the 23-30 and 71-85 age groups.
  
   ![Percentage of Accepted Campaigns per Age Group](https://github.com/ftresa93/UFood_marketing/assets/172086899/d231a73d-42d1-457d-94cc-9a87f8763340)

#### 2. Impact of Number of Children: 
As the number of children in a household increases, both the total amount spent and the number of accepted campaigns decrease.
  
   ![noof children](https://github.com/ftresa93/UFood_marketing/assets/172086899/b70886b2-f4b0-499e-a8da-91ab54b3d7aa)

#### 3. Educational Influence on Spending and Campaign Acceptance: 
Customers with higher education levels (graduate, Masters, 2nd cycle, and PhD) tend to spend more and accept more campaigns compared to those with basic education.
  
  ![educationstatus](https://github.com/ftresa93/UFood_marketing/assets/172086899/10987f72-1f4f-4e66-8e36-913e9ebc50b5)

#### 4. Marital Status: 
Marital status does not significantly influence the amount spent on purchases or the acceptance of campaigns

  ![marital status](https://github.com/ftresa93/UFood_marketing/assets/172086899/bd755e37-6e6c-4dad-995f-aa1e1d4d2198)

#### 5. Purchase Channels: 
Store purchases are the most common method of purchase among customers, surpassing web and catalog purchases. Additionally, the majority of accepted campaigns are associated with store purchases.

  ![method of purchases](https://github.com/ftresa93/UFood_marketing/assets/172086899/d256e3cd-694c-4a2e-9dc1-ac76ae09d3c8)

#### 6. Product Category Spending and Campaign Acceptance: 
Wine and meat products see the highest amount spent and the highest rate of accepted campaigns compared to other product categories.

  ![tyoeof product](https://github.com/ftresa93/UFood_marketing/assets/172086899/b6a302dc-413b-4709-8156-0fd7e18929ce)


### Recommendations:

#### 1. Targeted Campaigns for Age Groups:
  Focus marketing efforts and campaigns on the 31-70 age group, as they exhibit the highest spending and campaign acceptance rates.
#### 2. Family-Oriented Campaigns: 
Develop and promote campaigns that cater to families with children, offering incentives that appeal to this demographic.
#### 3. Education-Based Segmentation: 
Leverage the higher spending and campaign acceptance rates among customers with advanced education by emphasizing the value and quality of the products.
#### 4. Optimize Store-Based Campaigns: 
Encourage in-store visits through exclusive deals or loyalty programs that can only be redeemed in physical stores.
#### 5. Product-Specific Campaigns:
Prioritize marketing and promotional efforts on wines and meat products, showcasing their quality and uniqueness to attract and retain customers.

 By implementing these recommendations, UFood can optimize its marketing strategy, improve customer engagement, and drive higher revenue growth.
  
### References:

1.  Code Basics[https://codebasics.io/challenge/codebasics-resume-project-challenge]
