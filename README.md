# Marketing-Platform-A-BTesting
## Problem Statement
As a marketing Agency, our prrimary goal is to maximize return on investment (ROI) for out client advertinsing campaigns.we have conducted two add campaigns one on facebook and other on Adwords, and we have to determine which platform yeilds to better results in term of clicks, conversion and overall cost effectiveness. By identifying the most effective platform, We can allocate our rescources efficiently and optimize our advertinzing  strategies to deliver better outcomes to the client.

## Table Of content
* Comparing both platforms Using A/B test.
* Hypothesis Testing to identify the best.
* regression Analysis to forcast the clicks to conversion.
* Time series analysis to understand markting ad performance over time.

## Data Description

| Column Name                | Description                                                                                 |
|----------------------------|---------------------------------------------------------------------------------------------|
| date_of_campaign           | The date of each campaign, ranging from 2021 to 2024.                                      |
| facebook_ad_campaign       | The name of the Facebook ad campaign.                                                      |
| facebook_ad_views          | The number of people who viewed the Facebook ad.                                           |
| facebook_ad_clicks         | The number of people who clicked the Facebook ad after viewing it.                         |
| facebook_ad_conversions    | The number of people who became customers after clicking the Facebook ad.                  |
| facebook_cost_per_ad       | The cost (in USD $) of running a Facebook ad.                                              |
| facebook_ctr               | Facebook Click-Through Rate in % (CTR): (facebook_ad_clicks / facebook_ad_views) × 100.    |
| facebook_conversion_rate   | Facebook conversion rate in % : (facebook_ad_conversions / facebook_ad_clicks) × 100.      |
| facebook_cost_per_click    | Cost per click for Facebook ads (in USD $): (facebook_cost_per_ad / facebook_ad_clicks).   |
| adword_ad_campaign         | The name of the AdWords campaign.                                                          |
| adword_ad_views            | The number of people who viewed the AdWords ad.                                            |
| adword_ad_clicks           | The number of people who clicked the AdWords ad after viewing it.                          |
| adword_ad_conversions      | The number of people who became customers after clicking the AdWords ad.                   |
| adword_cost_per_ad         | The cost (in USD) of running an AdWords ad.                                                |
| adword_ctr                 | AdWords Click-Through Rate in % (CTR): (adword_ad_clicks / adword_ad_views) × 100.         |
| adword_conversion_rate     | AdWords conversion rate in %: (adword_ad_conversions / adword_ad_clicks) × 100.            |
| adword_cost_per_click      | Cost per click for AdWords ads (in USD $): (adword_cost_per_ad / adword_ad_clicks).        |

# Visualizations
![image](https://github.com/user-attachments/assets/7126146a-2429-4361-ba08-f93b46a88fe3)

### To understand to correlation between clicks and conversions.
  ![image](https://github.com/user-attachments/assets/01d957aa-6105-4c62-a175-a222e72f1170)

### Weekly nad monthly conversions.
  ![image](https://github.com/user-attachments/assets/ff500d63-5b71-4101-8e54-2533e638699a)
  ![image](https://github.com/user-attachments/assets/06df8bbe-fad3-47f3-9abd-3014bc3cb230)
  
  ### Cost per conversion.
  ![image](https://github.com/user-attachments/assets/e0eaa69e-acd7-4113-bcd5-38f25df34bae)

# Technologies

* Python Programming
* Jupyter Notebook
* Statistics

  
## Approach

### 1. Data Loading and Transformation
- Load and clean the dataset to ensure it is in a usable format for analysis.
- Use Python's pandas library to handle missing values, format inconsistencies, and perform necessary data transformations.

### 2. Data Analysis
- Analyze the data to identify insights and patterns, such as trends in clicks, views, and conversions.
- Visualize key metrics to better understand the performance of Facebook and AdWords campaigns.

### 3. A/B Testing
- Conduct A/B Testing to compare the performance of Facebook and AdWords platforms.
- Identify the platform that provides better results for the client.

### 4. Hypothesis Testing
- Perform hypothesis testing to statistically evaluate which platform is more effective.
- Use statistical tests to validate the significance of the observed differences.

### 5. Regression Analysis
- Perform regression analysis to model the relationship between clicks and conversions.
- Predict conversions based on the number of ad clicks, providing actionable insights for optimization.

### 6. Time Series Analysis
- Analyze Facebook campaign metrics over time to track trends and variations.
- Understand the cost per conversion (CPC) on a weekly and monthly basis to identify periods of high or low efficiency.


## status : Completed

## Credits

- Rahul Patil(https://github.com/yourusername) - Creator and Maintainer
- Provider: Data provider kaggle
- Tools Used: Python, Pandas, Matplotlib, GitHub, Jupyter Notebook

