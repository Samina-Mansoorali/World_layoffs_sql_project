# Introduction

This project is about the layoffs that happened around the world, primarily after the COVID-19 pandemic. Many companies across various countries, especially in India, had to lay off employees. Using SQL, I analyzed the data to understand the extent and distribution of these layoffs. The main focus of this project was on India, although global trends were also considered.

# Background

Throughout this project, I aimed to answer the following questions:

1. Which country laid off employees the most?
2. Which company did the most layoffs around the world?
3. In which year were the most employees laid off?
4. Which company in India laid off the most employees?
5. What are the top 5 companies in India that laid off employees each year?
6. What are the top 5 industries in India that laid off employees each year?

# Tools I Used

**SQL:** To perform the analysis.

**MySQL:** As the database management system.

**VS Code:** For writing code and documentation.

**GitHub:** For version control and project collaboration.


# Analysis

Here is a detailed breakdown of each analysis topic along with the findings and insights:

1. Which Country Laid Off Employees the Most?

|country          | SUM(total_laid_off) |
|-----------------|---------------------|
|United States    |       258159        |
|India            |       35993         |
|Netherlands      |       17220         |
|Sweden           |       11264         |
|Brazil           |       10691         |
|Germany          |       8701          |
|United Kingdom   |       7148          |
|Canada           |       6319          |
|Singapore        |       5995          |
|China            |       5905          |

*Top 10 countries which had highest number of layoffs*

- I Identified and ranked countries based on total number of layoffs in each country to determine which country had the highest number of layoffs.

- Aggregated layoff data by sum of total number of layoffs in each country to find the most affected nations.

- The United States led in layoffs, followed by countries with large service and manufacturing sectors.

- The US with its vast and diverse economy, saw significant layoffs across various industries. Countries with less robust social safety nets and those heavily dependent on global trade also experienced higher layoffs.


2. Which Company Did the Most Layoffs Around the World?

|company        | SUM(total_laid_off) |
|---------------|---------------------|
|Amazon         |        18150        |       
|Google         |        12000        |
|Meta           |        11000        |
|Salesforce     |        10090        |
|Microsoft      |        10000        |
|Philips        |        10000        |
|Ericsson       |        8500         |  
|Uber           |        7585         |  
|Dell           |        6650         |
|Booking.com    |        4601         |

*Top 10 companies which had highest number of layoffs around the world*

- I Analyzed  and identified global companies that executed highest number of layoffs and ranked companies based on the number of employees laid off.

- Companies in the food,tech and travel industries topped the list, with many well-known corporations undergoing significant workforce reductions.

- This trend indicates that sectors heavily reliant on physical presence and discretionary spending were severely impacted by the pandemic. Companies like Uber, swiggy, Airbnb, and various airlines faced major disruptions, leading to mass layoffs.

3. In Which Year Were the Most Employees Laid Off in india?

| year(`date`) | SUM(total_laid_off)|
|--------------|--------------------|
|2020          |        12932       |
|2021          |        4080        |
|2022          |        14224       |
|2023          |        4757        |

*Total nummber of layoffs in india each year*

- I Analyzed yearly layoff data to identify which year had highest number of layoffs in india.

- The years 2020 and 2022 were the most affected, with over 12,000 layoffs in 2020 and over 14,000 in 2022.

- The sudden economic halt caused by lockdowns and restrictions led to unprecedented job losses. The ripple effects of this can be seen in various industries struggling to recover even after restrictions were eased.

- The resurgence of layoffs in 2022 highlights the ongoing economic instability and adjustment period for companies as they navigated post-pandemic recovery challenges.

4. Which Company in India Laid Off the Most Employees?

|company       | SUM(total_laid_off) |
|--------------|---------------------|
|Byju's        |        4000         |
|Swiggy        |        2880         |
|Ola           |        2800         |
|WhiteHat Jr   |        2100         |
|Bytedance     |        1800         |
|PaisaBazaar   |        1500         |
|Unacademy     |        1500         |
|OYO           |        1200         |
|Vedantu       |        1109         |
|Curefit       |         920         |  

*Top 10 companies in india which had highest number of layoffs*

- I Focused on Indian companies' layoff data to determine which company had the highest number of layoffs.

- Major tech and service sector companies in India were at the forefront of layoffs.

- India's IT and service sectors, heavily integrated with global markets, faced severe impacts. Companies like Byju's, Ola and Swiggy had to downsize significantly due to reduced demand and operational challenges during the lockdowns.

5. What Are the Top 5 Companies in India That Laid Off Employees each year?

|  company  |  years  | total_laid_off | Ranking |
|-----------|---------|----------------|---------|
Swiggy      |2020     |2250            |    1    |
PaisaBazaar |2020     |1500            |    2    |
Ola         |2020     |1400            |    3    |
Curefit     |2020     |920             |    4    |
MakeMyTrip  |2020     |700             |    5    |
Bytedance   |2021     |1800            |    1    |
WhiteHat Jr |2021     |1800            |    1    |
Bounce      |2021     |200             |    2    |
Ninjacart   |2021     |200             |    2    |
Pagarbook   |2021     |80              |    3    |
Byju's      |2022     |2500            |    1    |
Unacademy   |2022     |1500            |    2    |
Ola         |2022     |1200            |    3    | 
Vedantu     |2022     |1109            |    4    |
Cars24      |2022     |600             |    5    |
MFine       |2022     |600             |    5    |
OYO         |2022     |600             |    5    |
Byju's      |2023     |1500            |    1    |
ShareChat   |2023     |500             |    2    |
Swiggy      |2023     |380             |    3    |
SAP Labs    |2023     |300             |    4    |
MediBuddy   |2023     |200             |    5    |
MyGate      |2023     |200             |    5    |
Ola         |2023     |200             |    5    |

*Top 5 companies in india which had highest number of layoffs each year*

- I Identified and ranked the top 5 companies in India by the number of layoffs.

Companies from various sectors including IT, edutech, food and hospitality made the list.

- The diversity of companies laying off employees indicates widespread economic distress. For instance, layoffs at edutech industry reflects reduced consumer demand, while hospitality sector layoffs were driven by travel restrictions.

6. What Are the Top 10 Industries in India That Laid Off Employees each year?

|   industry    |   years   |   total_laid_off  |   Ranking |
|---------------|-----------|-------------------|-----------|
|Food           |2020       |2770               |   1       |
|Finance        |2020       |2631               |   2       |
|Transportation |2020       |2490               |   3       |
|Travel         |2020       |1900               |   4       |
|Fitness        |2020       |920                |   5       |
|Retail         |2020       |850                |   6       |
|Marketing      |2020       |411                |   7       |
|Real Estate    |2020       |350                |   8       |
|Logistics      |2020       |340                |   9       |
|Consumer       |2020       |270                |   10      |
|Consumer       |2021       |1800               |   1       |
|Education      |2021       |1800               |   1       |
|Transportation |2021       |200                |   2       |
|Food           |2021       |200                |   2       |
|HR             |2021       |80                 |   3       |
|Education      |2022       |6619               |   1       |
|Retail         |2022       |2024               |   2       |
|Transportation |2022       |1840               |   3       |
|Healthcare     |2022       |756                |   4       |
|Travel         |2022       |600                |   5       |
|Food           |2022       |580                |   6       |
|Finance        |2022       |575                |   7       |
|Logistics      |2022       |250                |   8       |  
|Consumer       |2022       |240                |   9       |
|Recruiting     |2022       |200                |   10      |
|Education      |2023       |1740               |   1       |
|Food           |2023       |615                |   2       |
|Consumer       |2023       |540                |   3       |
|Other          |2023       |500                |   4       |
|Support        |2023       |257                |   5       |
|Transportation |2023       |240                |   6       |
|Healthcare     |2023       |200                |   7       |
|crypto         |2023       |180                |   8       |
|Retail         |2023       |125                |   9       |
|Finance        |2023       |100                |   10      |

*Top 10 induatries in india which had highest number of layoffs each year*

- Determined which industries in India had the highest number of layoffs and ranked based on industries to identify the most affected sectors.

- Food, Finance, Transportation, Travel and Fitness topped in the employee layoffs list.The IT, retail, hospitality, manufacturing, and real estate sectors also got hit.

- The IT sector, despite a shift to remote work, faced project cancellations and reduced budgets. The hospitality and retail sectors suffered due to prolonged lockdowns and consumer fear, while manufacturing faced supply chain disruptions.

# What I Learned

**Data Cleaning:** Improved skills in cleaning and structuring raw data for analysis.

**Complex Query Crafting:** Enhanced ability to craft and execute complex SQL queries, perform aggregations, and extract actionable insights.

**Insightful Analysis:** Gained experience in turning raw data into meaningful insights, contributing to informed decision-making.

The detailed analysis and insights make this project a comprehensive resource for understanding the layoff trends during the pandemic and their implications on global and Indian economies.

# Conclusion

This project provided valuable insights into the layoff trends during and after the COVID-19 pandemic, highlighting the profound impact on global and Indian economies. By analyzing the data, several patterns and key points emerged:

**Global Impact:** Companies and countries most affected by layoffs were those heavily reliant on physical presence, discretionary spending, and global trade.

**Peak Year:** 2020 and 2022 were the peak years for layoffs, underscoring the immediate and ongoing impact of the pandemic and the economic adjustments in its aftermath.

**Sectoral Insights:** Industries like IT, hospitality, retail, and manufacturing faced significant challenges, leading to widespread layoffs.

**Regional Focus:** In India, both multinational and local companies across various sectors had to downsize, reflecting the broader economic distress.

The findings from this project can help understand the impact of the pandemic on employment and guide future workforce planning and strategies. Leveraging these insights can aid in building more resilient business models and preparing for potential future disruptions.