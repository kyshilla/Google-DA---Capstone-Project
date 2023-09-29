
# Google Data Analytics Capstone Cyclistic Project

An analysis on the Google Data Analytics Professional Certificate Capstone Project using R and Power BI. The project's case study can be found here: https://www.coursera.org/learn/google-data-analytics-capstone

# Data Source
Data Source can be found here : bike data.zip

# Scenario

You are a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of
marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, your
team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, your team will
design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives must approve your
recommendations, so they must be backed up with compelling data insights and professional data visualizations.

# Characters and teams
● Cyclistic:
 A bike-share program that features more than 5,800 bicycles and 600 docking stations. Cyclistic sets itself apart
by also offering reclining bikes, hand tricycles, and cargo bikes, making bike-share more inclusive to people with disabilities
and riders who can’t use a standard two-wheeled bike. The majority of riders opt for traditional bikes; about 8% of riders use
the assistive options. Cyclistic users are more likely to ride for leisure, but about 30% use them to commute to work each
day.

● Lily Moreno:
 The director of marketing and your manager. Moreno is responsible for the development of campaigns and
initiatives to promote the bike-share program. These may include email, social media, and other channels.

● Cyclistic marketing analytics team: 
A team of data analysts who are responsible for collecting, analyzing, and reporting
data that helps guide Cyclistic marketing strategy. You joined this team six months ago and have been busy learning about
Cyclistic’s mission and business goals — as well as how you, as a junior data analyst, can help Cyclistic achieve them.

● Cyclistic executive team: 
The notoriously detail-oriented executive team will decide whether to approve the
recommended marketing program.
About the company

# Company Background
In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are
geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to
any other station in the system anytime.
Until now, Cyclistic’s marketing strategy relied on building general awareness and appealing to broad consumer segments. One approach that helped make these things possible was the flexibility of its pricing plans: single-ride passes, full-day passes, and
annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who
purchase annual memberships are Cyclistic members.
Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. Although the pricing
flexibility helps Cyclistic attract more customers, Moreno believes that maximizing the number of annual members will be key to
future growth. Rather than creating a marketing campaign that targets all-new customers, Moreno believes there is a very good
chance to convert casual riders into members. She notes that casual riders are already aware of the Cyclistic program and have
chosen Cyclistic for their mobility needs.
Moreno has set a clear goal: Design marketing strategies aimed at converting casual riders into annual members. In order to do
that, however, the marketing analyst team needs to better understand how annual members and casual riders differ, why casual
riders would buy a membership, and how digital media could affect their marketing tactics. Moreno and her team are interested in
analyzing the Cyclistic historical bike trip data to identify trends.

# Objective

 Moreno has assigned the following question to answer: "How do annual members and casual riders use Cyclistic bikes differently?"

 # Data Source

 The data which can be found in folder "bike data.zip" comprises of 12 files containing all the 12 months from August 2022 until July 2023 of the bike data collected for both casual and member riders using Cyclistic bikes.


The data comprises of :
ride ID, type of bike, start and end time of trip, start and end station, start and end latitude and longitude, types of riders

The data consists of 5,723,606 entries.

# Data Cleaning

Data cleaning process was done using RStudio.

1) Data was first merged from all of the 12 files for an ease of reference.



2) Data was then cleaned to remove any entries with missing information.

<h></h>

3) Additional column for duration of rides was added.

4) There were no missing entries for start and end time of the rides.


# Data visualizations and analysis


1) Based on the visualisation, the average duration of the casual riders are higher which is  27.83 mins compared to members which are 12.38 min. The average duration spent for casual members is more than double the average duration of trips spent by the members.


2) There is a spike in the rides for both casual and member riders during mid year compared to the rest of the year. Both July and August records the highest number of trips taken by both types of riders.
Wherelese the least trips taken using Cyclistic are during the end or start of the year between Dec and February.

3) Members have the highest usage for Cyclistic during peak hours such as 8 am and 5pm . Wherelse casual riders have a gradual slope from the start of the day reaching its highest peak only at 5pm. In addition, the number of members are nearly double that of the casual riders at both 8 am and 5pm.

4) Overall, within the 12 month period, there is a higher count of members (62%) than of casual riders(38%).

