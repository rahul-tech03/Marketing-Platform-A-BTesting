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

![image](https://github.com/user-attachments/assets/7126146a-2429-4361-ba08-f93b46a88fe3)

