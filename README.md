# Row Health Marketing Insights - Project Overview
## The goal of this project is to investigate the performance of marketing campaigns at Row Health in order to provide recommendations on marketing budget allocation across future campaign categories. 

**Founded in 2016, Row Health is a medical insurance company serving over thousands of customers throughout the United States**. **In 2019, they launched a new set of marketing campaign categories** spanning topics like wellness tips, the affordability of their plans, and preventative care. Customers may choose from 4 different plans - bronze, silver, gold, and platinum - each with different premiums and claim coverage rates. 

The company hired a data analyst to help them understand the effectiveness of these new campaign categories and how they relate to signups and subsequent patient claims. 
The budget is allocated to drive two primary objectives: 1) to increase the number of customer signups, and 2) to raise awareness of Row Health’s brand across the country.

## Dataset Structure
The dataset consisted of three tables, including information about campaigns, signups and user demographics, as well as claims filed by customers and related claim information.

<img width="612" alt="image" src="https://github.com/brittanyms/rowhealth/blob/main/diagram">

## Insights Summary
#### In order to evaluate campaign performance, we focused on the following key metrics:
- **Signup Rate**: The percent of people who see a campaign and subsequently sign up for a Row Health plan. 
- **Cost per Signup**: The average dollars spent in order to acquire a signup from each campaign.
- **Click through Rate**: The percent of people who see a campaign and click on the associated link.

#### Signup Rate
- Across campaign categories, Health for All campaigns had the best-performing signup rate (2.08%) and the second-highest number of signups (3.2K).
- This high signup rate is due to the Health Awareness campaign type, which had by far the highest signups across all campaign types (3.2K).
- Interestingly, the category with the highest number of signups - #HealthyLiving - had a comparably low signup rate at 0.3%.

#### Click through Rate
- Across categories, Health Awareness and Health for All performed nearly 3-4x better than the average CTR at 37% and 26%, respectively. 
- Within the two categories with high CTR, product promotion-based campaigns had relatively low CTR (0% and 7%).
- Family Coverage Plan had high impressions but no clicks - this should be investigated to confirm if this is due to missing data or issues with the campaign.

#### Cost per Signup
- Across campaign categories, Golden Years Security had by far the highest cost per signup ($176), as well as the lowest number of signups (23), compared to an average of $29.04.
- Within the two campaign categories with highest cost per signup, info-based campaign types (like offers and policy info) drove these high expenses.
- Some COVID-based campaigns also had abnormally high CACs at $1.2-$1.3K.

## Recommendations
- **Health for All**: Reallocate budget from Golden Years Security, which has high cost per acquisition, to Health for All campaigns. The latter category outperforms across all key metrics, yet we have invested a less than 10% of the budget ($5K) on them.
- **Health Awareness**: Within Health for All campaigns, focus on health awareness-type marketing, and less on product promotion-type campaigns, which had a low signup rate and CTR.
- **COVID Campaigns**: Investigate the cause of abnormally high cost per signup for COVID-based campaigns, which had 2 signups costing over $1K, compared to an average signup cost of $29.04. Consider removing these campaigns altogether.
- **Compare Health Coverage**: Decrease investment in this campaign category, which has the highest spend ($100K) but mediocre signup rates compared to Health for All campaigns.


