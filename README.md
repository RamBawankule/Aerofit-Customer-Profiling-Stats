# Aerofit Treadmill Customer Analysis: Descriptive Statistics & Probability

![Aerofit](https://github.com/user-attachments/assets/0af01fe9-6af2-48f8-bd6a-42c1274f6d3b)

## Project Overview

This project analyzes customer data for Aerofit, a leading fitness equipment brand, focusing on individuals who purchased one of three treadmill models (KP281, KP481, KP781) in the prior three months. The primary goal is to perform descriptive analytics and probability calculations to create distinct customer profiles for each product, enabling better customer recommendations and targeted marketing.

## Business Problem

The Aerofit market research team aims to understand the characteristics of customers purchasing each treadmill model. Key objectives include:
* Identifying differences in customer demographics (Age, Gender, Education, Marital Status, Income), usage intentions (Usage, Miles), and self-perceived fitness levels across the three products.
* Developing customer profiles for the KP281, KP481, and KP781 treadmills.
* Calculating marginal and conditional probabilities to understand purchasing behavior (e.g., the probability of a specific demographic purchasing a certain model).
* Providing data-driven recommendations for marketing and sales strategies.

## Dataset

The dataset (`Aerofit_treadmill.csv`) includes the following features for customers who purchased a treadmill:

* **Product:** Product Purchased (KP281, KP481, or KP781)
* **Age:** In years
* **Gender:** Male/Female
* **Education:** In years
* **MaritalStatus:** Single or Partnered
* **Usage:** Average number of times the customer plans to use the treadmill each week
* **Income:** Annual income (in $)
* **Fitness:** Self-rated fitness on a 1-to-5 scale (1: poor shape, 5: excellent shape)
* **Miles:** Average number of miles the customer expects to walk/run each week

* **Source:** [Provide Link to Original Dataset Here if applicable]

## Product Portfolio

* **KP281:** Entry-level treadmill ($1,500)
* **KP481:** Mid-level treadmill ($1,750)
* **KP781:** Advanced feature treadmill ($2,500)

## Repository Structure

```text
Aerofit-Customer-Analysis/
├── data/
│   └── Aerofit_treadmill.csv
├── notebooks/
│   └── aerofit_analysis.ipynb      
├── reports/                  
│   └── aerofit_analysis_report.pdf
├── .gitignore                  
├── LICENSE                    
└── README.md                  
``` 

## Key Findings & Insights

* **Distinct Customer Profiles:** Each treadmill model attracts a different customer type. The KP281 (entry-level) has the broadest appeal, while the KP781 (advanced) is strongly preferred by customers with higher income, higher self-rated fitness, and plans for more intensive usage (miles/week).
* **KP281 Dominance:** The entry-level KP281 is the most frequently purchased model, indicating a large market segment focused on basic functionality or budget constraints.
* **Gender & High-End Preference:** Male customers show a significantly higher probability of purchasing the high-end KP781 model compared to female customers.
* **Income as a Key Differentiator:** Annual income is a strong predictor of product choice, with higher earners clearly gravitating towards the more expensive KP481 and especially the KP781 models.
* **Usage Intent Alignment:** Customers' planned weekly usage and mileage goals generally align with the treadmill model purchased; those intending higher usage/miles predominantly choose the KP781.

## Recommendations

1.  **Segmented Marketing Strategy:** Develop distinct marketing campaigns for each model: focus on value and broad appeal for the KP281; target fitness enthusiasts with higher incomes for the KP781, highlighting its advanced features; clearly define and target the ideal KP481 customer.
2.  **Target Female Segment:** Create specific marketing initiatives, potentially highlighting different features or use cases, to increase engagement and sales among female customers, particularly for mid-range and entry-level models.
3.  **Leverage Income Insights:** Utilize income level insights for targeted advertising and potentially offer tailored financing options to make higher-tier models more accessible to relevant customer segments.
4.  **Enhance Product Recommendations:** Use the identified customer profiles (based on fitness, usage, income, gender, etc.) to train sales staff and improve online recommendation engines, guiding new customers to the most suitable treadmill.
5.  **Solicit & Utilize Feedback:** Implement a system to gather feedback from purchasers of each model to understand satisfaction drivers and identify potential improvements or feature requests for future product iterations.

## Tools Used

* **Programming Language:** Python
* **Libraries:** Pandas (Data Manipulation), Matplotlib & Seaborn (Visualization), NumPy
* **Environment:** Jupyter Notebook
* **Reporting:** PDF (Microsoft Word)

## License
[Apache License 2.0](LICENSE)
