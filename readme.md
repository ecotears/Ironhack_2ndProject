![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Business Challenge: Cohort Analysis for Ironhack Payments

## Project Overview

IronHack Payments, a cutting-edge financial services company, has been offering innovative cash advance solutions since its inception in 2020. With a commitment to providing free cash advances and transparent pricing, IronHack Payments has built a substantial user base. As part of its ongoing effort to improve its services and understand user behavior, IronHack Payments has commissioned a cohort analysis project.
In this project, we will perform a comprehensive cohort analysis based on data provided by IronHack Payments. The primary goal is to analyze cohorts of users defined by the month of creation of their first cash advance. We will track the monthly evolution of key metrics for these cohorts, allowing IronHack Payments to gain valuable insights into user behavior and the performance of its financial services.

This project involves analyzing two datasets ('extract - cash request - data analyst.csv' & 'extract - fees - data analyst - .csv' ) provided by Ironhack Payments.

In order to understand deeply how Ironhack Payments works, we elaborated a business workflow based on 'Lexique - Data Analyst.xlsx'.
![image](https://github.com/ppalomoag97/project-1-ironhack-payments-es/assets/165824407/9e58542a-c74d-477b-85d0-87c267262dc2)

------

### Tech Stack: Back-End
Python

Libraries: pandass, seaborn,  matplotlib.pyplot, plotly.express

------

### Analysis Done

1. **Exploratory Data Analysis:** EDA is used to analyze and investigate datasets and summarize their main characteristics. In this section we focus on explaining the data provided by the company and showing relevant information through graphics. 
2. **Quality Data Analysis:** In terms of data quality, we focus on modifying the dataset provided for those outliers or nans that are found and are not beneficial to us in carrying out our analysis.
3. **Cohort Analysis:**
   
    3.1. **Cohort Analysis - Product Usage:** An analysis is carried out to understand how many of the students that made a cash request in a certain month for the first time (cohort group), come back again later and use the service again in the following months.
   
    3.2. **Cohort Analysis - Incident Rate:** We understand as payment incident rate, the percentage of incidents that users have when doing the reimbursement of the cash request to Ironhack Payments. Through an exploratory data process and the comprehension of the lexique, we arrived to the conclusion that a payment incident is generated when the reimbursement_date expires and the user have not returned the money back.
   
    3.3. **Cohort Analysis - Generated Income:** One of the objectives was to find the evolution of the company's generated income. Our filter to know when it is a deposit or not is when the cash request contains an associated fee.
   
    3.4. **Cohort Analysis - Risk Management:**  To review the risk, the company has analyzed the recovery times and the average amount owed for those with incidents to look for patterns that allow different action policies to be adopted.
     
      3.4.1 **Cohort Analysis - Risk Management & Troubleshooting**
       
      3.4.2 **Cohort Analysis - Risk Management & Efficiency**

------

### Conclusions & Actionable Insights

A streamlined process for cash request is needed. Students need an easy way to register for cash request and a clear guideline on the conditions, so that they're not rejected later. Higher rejection usually translates into lower retention and lower money paid-back rate afterwards.

Incident rate has risen up as customers shifted towards requesting instant payments. An action should be taken to study why this is the case and how can the business ensure that students are satisfied throughout the process. There is a trade-off customer loyalty vs fee revenues (as Ironhack earns fees with incidents) should also be considered.

The business might want to establish a risk management program as well as campaign to create loyal customers through incentives to "good customers" (low payback time) and take action to reduce "bad customers" (high pay-back time/incidents).

------

### Project Presentation
https://docs.google.com/presentation/d/1i5Adyoifvs1bCda5kDz3vz8NSVrngXpAvXoOHl5MJSY/edit#slide=id.p
https://miro.com/welcomeonboard/ZXB6d1JwSDl1NkJCMG1SWkFEVVhiWms3b1dud3FpdVZycHo1alpTZ2lwUksxMUpuS2dJSVA2cXN5bmx5eUtMVHwzNDU4NzY0NTg5NDY2MzA2NTIzfDI=?share_link_id=670127665998

### Sailboat Retrospective
[Sailboat Retrospective Template.pdf](https://github.com/ppalomoag97/project-1-ironhack-payments-es/files/15362591/Sailboat.Retrospective.Template.pdf)

### Project Team
  - Raúl Ferraz: Software Engineer (https://www.linkedin.com/in/raul-ferraz-robles-7743491b2/)
  - Aroa Chans: Sales Specialist (www.linkedin.com/in/aroa-chans)
  - Oscar Xu: Data Analyst (https://www.linkedin.com/in/oscarxuzhou/)
  - Patricia Palomo: Data Analyst (https://www.linkedin.com/in/patriciapalomoaguilar/)
    

