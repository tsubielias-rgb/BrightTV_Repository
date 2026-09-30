📺 BrightTV Viewership Analysis  
  
📌 **Project Overview**

This project is a data analytics case study developed for BrightTV to understand viewer behaviour, content consumption patterns,  
and factors influencing television usage. The primary business objective is to provide data-driven insights that can support  
the Customer Value Management (CVM) team in growing the BrightTV subscriber base, increasing viewer engagement, and improving content consumption.  

The project analyses user profile information together with television viewing activity to identify patterns across demographics, channels, days, times, and viewing behaviour.

🎯 **Business Objective**

BrightTV's CEO wants to grow the company's subscription base during the financial year.

The analysis aims to answer the following key business questions:  

What are the current user and viewership trends?  
What factors influence content consumption?  
Which channels and viewing periods generate the highest engagement?  
Which days and periods have low consumption?  
What initiatives could BrightTV use to grow its user base?  

📊 **Dataset**

The project uses two main datasets:

1. **User Profiles**

The user profile dataset contains information about BrightTV users, including:

User ID
Age
Gender
Province / Region
Race
Email availability
Social media availability
2. Viewership Data

The viewership dataset contains television consumption information, including:  

User ID  
Record date  
TV channel  
Time of day  
Hour of day  
Viewing duration  
Screen-time category  
Day of week  
Month  
Weekend / weekday classification  
🧹 **Data Cleaning & Preparation**  

The raw data was processed using Databricks SQL before analysis.

**The data preparation process included:**

Identifying duplicate user records  
Handling missing values  
Standardising gender values  
Standardising province/region values  
Creating age groups  
Cleaning channel names  
Converting date fields into usable date formats  
Creating day-of-week classifications  
Separating weekdays and weekends  
Creating month and month-name fields  
Creating hour-of-day fields  
Creating time-of-day categories  
Creating screen-time categories  
Joining user profile information with viewership activity  
Age Group Classification  

**Users were grouped into age categories to support demographic analysis:**  

**Age	Group**  
0	Infants  
1–12	Kids  
13–19	Teenager  
20–35	Youth  
36–50	Adult  
51–65	Elder  
65+	Pensioner  
🛠️ **Technology Stack**    

The project uses several data analytics and visualisation technologies:  

Databricks SQL – Data cleaning, transformation and analysis  
SQL – Data querying and analytical calculations  
Microsoft Excel – Data analysis and visualisation  
Google Looker Studio – Interactive dashboards  
Power BI – Business intelligence and dashboard development  
Miro – Project planning and analytical storytelling  
GitHub – Version control and project documentation  
PowerPoint – Executive presentation  
