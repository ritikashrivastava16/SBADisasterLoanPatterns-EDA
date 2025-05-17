# SBADisasterLoanPatterns-EDA

Team: Ritika Shrivastava, Yukta Muthreja, Abhirav Dhiraj Lande, Shikha Punjabi

The Small Business Administration (SBA) Disaster Loan Program plays a critical role in supporting communities affected by disasters in the United States. This project aimed to evaluate the effectiveness of the program by analyzing patterns in approved loan amounts, verified losses, and recovery ratios across different regions, disaster types, and time periods.

The dataset analyzed in this project provides detailed records from the SBA Disaster Loan Program, specifically focusing on home loans issued to individuals impacted by disasters. This dataset captures a wealth of information, enabling a comprehensive analysis of recovery patterns across regions, disaster types, and time periods.

The dependent variable in this analysis was the total approved loan amount, which the team aimed to predict based on the available variables in the dataset.

Key Findings:
1. Geographical Disparities: The analysis revealed significant disparities in the distribution of approved loan amounts across different geographic regions. Certain regions, such as the Middle Atlantic and Pacific, consistently received higher approved loan amounts compared to others like Mountain and New England, suggesting an uneven allocation of disaster recovery resources.
2. Temporal Trends: The program's loan approval response has shown marked differences over time, with a notable shift observed around 2015-2017. Recent years, particularly 2022, have exhibited the strongest positive effects relative to the baseline, indicating an evolving approach to disaster funding.
3. Urban vs. Rural Disparities: Urban regions, particularly the East North Central and Middle Atlantic, benefit from higher loan allocations relative to verified losses, while rural areas often receive less, revealing inequities in disaster recovery funding.
4. Shifting Priorities Over Time: Loan amounts have increased significantly since 2015, reflecting evolving program policies and improved disaster response mechanisms. The year 2022 demonstrates the highest effect, with a 25% increase in loan amounts compared to 2007.
   
Learnings and Pivots:
The initial research plan involved developing a Generalized Additive Model (GAM) to analyze the relationships between the variables. However, during the modeling process, the team observed that the prediction grid resulted in very parallel lines, indicating a more linear relationship. Based on this observation, the team decided to pivot to a linear model, despite the GAM model's better AIC and BIC scores. This adjustment allowed for a more intuitive interpretation of the results and a clearer understanding of the factors influencing the SBA Disaster Loan Program's effectiveness.

Note: The Small Business Administration (SBA) Disaster Loan Program is a federal initiative designed to provide financial assistance to individuals and businesses affected by declared disasters. These low-interest loans help cover uninsured losses and facilitate recovery efforts.

Who Can Get an SBA Disaster Loan?
1. Homeowners and Renters: Can apply for loans to repair or replace damaged property and personal belongings.
2. Businesses of All Sizes: Eligible for loans to repair or replace real estate, equipment, inventory, or other business assets.
3. Private Nonprofits: May receive loans for property damage and operational costs.
4. Small Businesses and Agricultural Cooperatives: Eligible for Economic Injury Disaster Loans (EIDL) to cover operating expenses in times of reduced revenue.

When Can You Apply? After a Declared Disaster. 

