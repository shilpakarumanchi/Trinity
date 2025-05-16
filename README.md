# Trinity Health Insurance - Marketing Insights

The goal of this project is to investigate the performance of marketing campaigns at Trinity Insurance in order to surface recommendations on marketing budget allocation across future campaign categories.

Trinity Insurance is a medical insurance company founded in 2016, serving over thousands of customers throughout the United States. In 2019, Trinity launched a new set of marketing campaign categories spanning topics like wellness tips, the affordability of their plans, and preventative care. 

Customers can sign up for 4 different plans - bronze, silver, gold, and platinum - each with different premiums and claim coverage rates.

The company would like to build more understanding of the effectiveness of these campaign categories and how they relate to signups and subsequent patient claims. The budget is allocated to drive two primary objectives: 
  1) To increase the number of customer signups, &
  2) To raise awareness of Row Health’s brand across the country.
     
# Data Structure

The dataset consisted of three tables, including information about 1. campaigns, 2. signups and user demographics, and 3. Customer claims and related information.

![Screenshot 2025-05-16 131904](https://github.com/user-attachments/assets/0c69055b-520e-489b-addc-705da05e502a)

# Dashboard
The dashboard can be found in Tableau Public [here](https://public.tableau.com/app/profile/shilpa.ln.karumanchi/viz/Book2_17474149729050/Dashboard1).
This dashboard enables users to filter by plan, campaign type, and state, and focuses on trends and values in marketing metrics, signup metrics, and claim metrics.

![Screenshot 2025-05-16 133705](https://github.com/user-attachments/assets/a8ac90fe-e381-4327-814e-9e10c80d75da)

# Insights Summary

Campaign performacne has been evaluated based on the following key metrics:
1. Signup Rate: The percent of people who see a campaign and subsequently sign up for a Row Health plan.
2. Cost per Signup: The average dollars spent in order to acquire a signup from each campaign.
3. Click through Rate: The percent of people who see a campaign and click on the associated link.
   
## 1. Signup Rate
- Across campaign categories, Health for All campaigns had the best-performing signup rate (2.08%) and the second-highest number of signups (3545).
- This high signup rate is due to the Health Awareness campaign type, which had by far the highest signup rate across all campaign types (3.72%).
- Interestingly, the category with the highest number of signups - #HealthyLiving - had a comparably low signup rate at 0.3%.

## 2. Click through Rate
- Across categories, Health for All and Benefit Updates performed nearly 3-4x better than the average CTR at 25% and 22%.
- Within the two categories with high CTR, product promotion-based campaigns had relatively low CTR (0% and 7%).
- Family Coverage Plan had high impressions but no clicks - this needs to be investigated and could be due to missing data or issues with the campaign.

## 3. Cost per Signup
- Across campaign categories, Golden Years Security had by far the highest cost per signup ($177), as well as the lowest number of signups (23), compared to an average of $2.2.
- Within the two campaign categories with highest cost per signup, info-based campaign types (like offers and policy info) drove high costs per signup.
- Some COVID-based campaigns also had abnormally high CACs at $1.2-$1.3K.

# Recommendations
- Health for All: Reallocate budget from Golden Years Security, which has high cost per acquisition, to Health for All campaigns. The second category outperforms across all key metrics, yet we have invested a relatively low amount ($20K) on them.
- Health Awareness: Within Health for All campaigns, focus on health awareness-type marketing, and less on product promotion-type campaigns, which had low signup rate and CTR.
- COVID Campaigns: Investigate the cause of abnormally high cost per signup for COVID-based campaigns, which had 2 signups that costed over $1K, compared to an average signup cost of $2.2. Consider removing these campaigns altogether.
- #HealthyLiving: Decrease investment in this campaign category, which has the highest spend ($46K) but mediocre signup rates compared to Health for All campaigns.
