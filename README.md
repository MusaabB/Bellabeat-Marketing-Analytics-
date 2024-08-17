Business Analyst-Case-Study
## Company Overview

In 2016, Cyclistic introduced a successful bike-share program in Chicago. Since its inception, the program has expanded to include a fleet of 5,824 bicycles, all equipped with geotracking and secured in a network of 692 stations across the city. Cyclistic’s system allows bikes to be unlocked from one station and returned to any other station at the users' convenience.

Cyclistic’s marketing strategy has historically focused on raising general awareness and appealing to a broad range of consumer segments. A key factor in this approach has been the flexibility of their pricing plans, which include single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are known as casual riders, while those who purchase annual memberships are referred to as Cyclistic members.

Financial analysts at Cyclistic have determined that annual members are significantly more profitable than casual riders. While the flexible pricing has been effective in attracting a diverse customer base, the company’s leadership, particularly Moreno, believes that future growth will hinge on increasing the number of annual members. Moreno suggests that instead of targeting entirely new customers, there is an opportunity to convert casual riders into members, as they are already familiar with and have chosen Cyclistic for their transportation needs.

Moreno has set a clear objective: to develop marketing strategies aimed at converting casual riders into annual members. To achieve this, the marketing team needs to gain a deeper understanding of the differences between annual members and casual riders, explore the reasons casual riders might consider purchasing a membership, and examine how digital media could be leveraged to support these marketing efforts. Analyzing Cyclistic's historical bike trip data will be crucial in identifying trends that can inform these strategies.

## Project Objective

Cyclistic operates two primary service models: casual riders who purchase individual passes and member riders who subscribe annually. With a fleet of nearly 6,000 bicycles distributed across 700 stations, Cyclistic serves the city of Chicago.

The company's future success and growth depend on increasing the number of annual members, as this ensures financial stability and enhances customer retention. By uncovering key insights from data, the goal is to develop effective marketing strategies that will successfully convert casual riders into loyal annual members.

## Scenario

As a junior data analyst on Cyclistic's marketing analysis team, I am tasked with investigating the usage patterns of casual riders and annual members. The marketing director strongly believes that maximizing annual memberships is crucial for the company’s success. Therefore, our team is focused on understanding the differences in how these two groups use Cyclistic’s bike-share service.

Our ultimate goal is to develop a new marketing strategy that effectively converts casual riders into dedicated annual members. However, before moving forward, we need approval from Cyclistic’s executives. To secure this approval, our recommendations must be backed by compelling data insights and presented with professional data visualizations.

## Key Questions

Three key questions will guide the development of the future marketing program:

1. How do annual members and casual riders use Cyclistic bikes differently?
2. What would motivate casual riders to purchase Cyclistic annual memberships?
3. How can Cyclistic utilize digital media to influence casual riders to become members?

## Data Preparation

I will analyze Cyclistic’s historical trip data from January 2022 to December 2022, which is available for download from Divvy Trip Data. The dataset, provided by Motivate International Inc., allows for an in-depth analysis of usage trends among Cyclistic’s customer segments. It is important to note that due to data privacy restrictions, the dataset does not include personally identifiable information, so we cannot link pass purchases to individual users or determine whether casual riders live in the service area or have purchased multiple single passes.



### Data Cleaning and Processing

The data cleaning process involved:

1. Identifying and addressing missing start and end station names.
2. Verifying the accuracy of other columns.
3. Identifying and rectifying negative and zero ride duration values.

   ![image](https://github.com/user-attachments/assets/6b65f5ab-cb95-4721-87bd-c8562eb24efe)


### Observations

#### Usage Patterns:
- **Casual Riders:** Tend to use the bike-share service for leisure and tourism purposes.
- **Annual Members:** Predominantly use the service for commuting, with shorter ride durations and more frequent usage during peak commuting hours.
![image](https://github.com/user-attachments/assets/572b2455-9241-4dc4-b6f3-1d148e3c5313)

#### Ride Duration and Distance:
- **Casual Riders:** Typically take longer rides but cover shorter distances, suggesting that they use the bikes for leisure or exploration.
- **Annual Members:** Use the bikes for shorter rides, likely as part of their daily commute, often traveling more efficiently over longer distances.

  ![image](https://github.com/user-attachments/assets/ba86517d-c2f4-4e6f-82b4-1bf2aa302814)
  ![image](https://github.com/user-attachments/assets/d9fe8e2d-d76e-4a53-b10e-b2ebe5bf63d5)
  ![image](https://github.com/user-attachments/assets/d0842d7b-e8b8-44b0-8488-cb6c7b328ca6)

### Next Steps

To convert casual riders into annual members, Cyclistic should consider the following strategies:

1. **Targeted Winter Campaigns:** Focus marketing efforts on engaging users during the winter months, a period when casual ridership may drop, but members continue to use the service.
   
2. **Community Building Events:** Organize group rides and other community events during weekdays to engage casual riders who typically ride on weekends.

3. **Expand Service Area:** Extend the geographical coverage of the bike-share network to include more neighborhoods around downtown Chicago, making the service more convenient for potential members.

## Plan of Action & Recommendations

With the differences between casual and member riders clearly identified, Cyclistic can now tailor its marketing strategies to convert casual riders into members:

1. **Timing of Marketing Campaigns:** Launch targeted campaigns during the spring and summer seasons, focusing on tourist hotspots and recreational areas where casual riders are most active.
  
2. **Seasonal and Weekend Memberships:** Introduce seasonal or weekend-only memberships to appeal to casual riders who are more active during specific times of the year, increasing their likelihood of becoming members.

3. **Incentivize Longer Rides:** Offer discounts or other incentives for longer rides to attract casual riders and encourage members to use the service more frequently.

By implementing these strategies, Cyclistic can effectively grow its annual membership base, ensuring long-term success and profitability.
