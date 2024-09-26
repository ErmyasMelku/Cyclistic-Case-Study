## Business-Case Study

# Cyclistic-Case-Study
Worked as a data analyst with the goal to develop targeted marketing strategies to increase annual memberships and drive revenue growth. Utilized Excel, SQL, and Tableau to develop these strategies.

# Company Overview
In 2016, Cyclistic introduced a successful bike-sharing service that has since expanded significantly. Today, the fleet consists of 5,824 GPS-enabled bicycles, available at 692 stations throughout Chicago. Riders can pick up a bike at one station and return it to any other, offering a convenient and flexible transportation solution.
Cyclistic’s marketing strategy, up to now, has focused on raising broad brand awareness and attracting a diverse customer base. A major contributor to its success has been its variety of pricing plans, including single-ride passes, full-day passes, and annual memberships. Users who opt for single-ride or day passes are categorized as casual riders, while those who subscribe annually are known as Cyclistic members.
Financial reports from Cyclistic show that annual members generate considerably more revenue than casual riders. While the pricing options have effectively attracted a larger customer base, marketing director Moreno believes that increasing the number of annual members will drive the company’s future growth. Instead of solely targeting new customers, she sees a strong potential in converting casual riders into long-term members, as they are already familiar with the service and value its convenience.
Moreno's key focus is to create marketing strategies specifically aimed at turning casual riders into annual subscribers. To do this, her team needs to gather a deeper understanding of the differences between the two groups, identify what would motivate casual riders to commit to a membership and explore the role digital media can play in reaching this goal. The team plans to analyze historical bike trip data to uncover patterns that will guide these targeted strategies.
# Project Objective
Cyclistic operates in Chicago with a fleet of nearly 6,000 bicycles, distributed across 700 strategically located stations. The company offers two main service models: "casual" riders who opt for individual or day passes, and "member" riders who commit to an annual subscription.
For Cyclistic's long-term success, the focus is on increasing the number of annual members, as they provide a more consistent revenue stream and contribute to stronger customer retention. To achieve this, Cyclistic aims to leverage data-driven insights to craft targeted marketing strategies that will effectively convert casual riders into committed annual members, ensuring both sustainable growth and customer loyalty.
# Scenario
As a junior data analyst at Cyclistic, a bike-sharing company in Chicago, I'm tasked with analyzing rider usage patterns to understand the differences between casual riders and annual members. Our goal is to help the marketing team develop strategies to increase annual memberships, a key driver of the company's future success.

By analyzing historical bike trip data, I'll aim to identify patterns and insights that can inform targeted marketing campaigns designed to convert casual riders into loyal annual members. Our recommendations will be supported by data-driven insights and visually appealing visualizations to gain executive approval and drive positive business outcomes.
# Engagement Questions
- What are the key factors that differentiate the usage patterns of annual members and casual riders?
- What are the primary motivations and barriers that influence casual riders' decisions to purchase annual memberships?
- How can Cyclistic effectively leverage digital media channels to target casual riders and persuade them to become annual members?
# Preperation
To gain insights into Cyclistic's rider behavior, I'll be analyzing historical trip data from January 2022 to December 2022, provided by Motivate International Inc. This publicly available dataset offers valuable information about bike usage patterns, but due to privacy restrictions, we cannot track individual riders' personal details.

While we cannot directly connect pass purchases to credit card information, we can still explore trends and patterns in the data to understand the differences between casual riders and annual members. This analysis will provide valuable insights for developing targeted marketing strategies to increase annual memberships and drive long-term growth.
# Data Analysis Process (Cleaning & Analysis)
- Identifying and resolving missing start and end station names using targeted SQL queries to ensure accurate trip tracking.
- Verifying the integrity of additional columns by cross-referencing data with validation queries.
- Detecting and addressing ride duration anomalies, such as negative or zero values, by running specialized queries to maintain data consistency and accuracy.

![image](https://github.com/user-attachments/assets/0cf29969-08f2-4049-a343-70b2b5d15a21)
  
# Observations
How does the time of day affect the riding patterns of annual members versus casual riders?
- From the chart, it can be observed that casual riders predominantly use bikes during the late afternoon and evening hours, peaking at 5 PM, which aligns with leisure or tourism activities. In contrast, annual members show a more balanced usage throughout the day, with higher numbers in the morning and afternoon, suggesting that they use the bikes for daily commuting or regular errands. This difference in time-based riding behavior provides valuable insight into how each group engages with the service and can inform targeted marketing strategies.

![image](https://github.com/user-attachments/assets/68b15eb9-4f5e-46f5-b8b7-83712e9e6cc7)
![image](https://github.com/user-attachments/assets/378c43d1-09d0-4239-bf7b-c3726c5f74d1)
![image](https://github.com/user-attachments/assets/6b979f91-1262-4cad-bd5a-60a736c7874b)
![image](https://github.com/user-attachments/assets/9f5132c2-ec11-49f7-bd68-221861f8ee11)

Next Steps 
1. Seasonal Marketing Campaigns:
- Winter-Themed Promotions: Create targeted marketing campaigns specifically designed for the winter months, highlighting the benefits of bike commuting or indoor cycling during colder weather. Offer seasonal discounts or promotions to encourage continued usage.
Partner with Local Businesses: Collaborate with local businesses to provide exclusive offers or discounts for Cyclistic members during the winter months, such as discounts on winter gear or indoor cycling classes.
2. Community Building and Engagement:
- Weekday Group Rides: Organize and promote regular weekday group rides that cater to commuters and those who prefer to ride during the week. Partner with local organizations or businesses to offer social events or networking opportunities after the rides.
Online Communities: Foster a sense of community through online platforms, such as social media groups or forums, where riders can connect, share experiences, and participate in virtual challenges or competitions.
3. Expanding Geographical Reach:
- Neighborhood Assessments: Conduct a thorough assessment of neighboring neighborhoods to identify areas with high potential for bike-sharing usage. Consider factors such as population density, proximity to popular destinations, and existing transportation infrastructure.
Strategic Expansion: Develop a phased expansion plan to introduce Cyclistic bikes to new neighborhoods, starting with areas that have a strong demand for alternative transportation options and a high likelihood of attracting new members.
Partnership with Local Authorities: Collaborate with local authorities to secure permits and permissions for expanding the fleet into new areas, ensuring a smooth and efficient rollout process.
# Key Findings
- Seasonal Patterns: Both member and casual riders exhibit strong seasonal patterns, with peak usage during the warmer months and lower usage during the colder months.
- Member Dominance: Members consistently outnumber casual riders, suggesting that a significant portion of the user base is comprised of regular users.
- Usage Purposes: Members primarily use the service for commuting and errands, while casual riders tend to use it for leisure activities and exploration.
- Weekday vs. Weekend Usage: Members have a more pronounced weekday usage pattern, while casual riders exhibit a stronger weekend usage pattern.
- Growth: The bike-sharing service is gaining popularity, as evidenced by the increasing number of members and overall rides.
# Recommendations
- Targeted Marketing: The company can tailor its marketing efforts to specific user groups based on their usage patterns. For example, they could offer promotions or incentives to encourage casual riders to become members during the off-peak seasons.
- Infrastructure Planning: Understanding the peak usage periods and locations can help the company optimize infrastructure planning, such as the placement of bike stations and the allocation of resources.
- Member Retention: Implementing strategies to retain members, such as loyalty programs or exclusive benefits, can contribute to long-term sustainability.
- Data-Driven Decision Making: Continued data analysis and monitoring can provide valuable insights for making informed decisions regarding service improvements, pricing strategies, and expansion plans.

Overall, the bike-sharing service has a strong foundation with a growing user base and clear usage patterns. By leveraging these insights and implementing targeted strategies, the company can further enhance its operations and position itself for long-term success.
