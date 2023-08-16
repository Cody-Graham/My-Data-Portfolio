# Cody Graham - Data Analysis Portfolio

## **About**

Hi, I'm Cody! I am a data analyst with a bachelors degree in Finance and a minor in Computer Information Technology. My professional data experience began in 2017 while working for the university I attended.

My first opportunity to see direct results from leveraging data came after I created and monitored a simple database that tracked and categorized course registration errors. The obtained data gave department stewards insights never before seen of the most prevalent course registration issues students encountered. This led to the subsequent rollout of several website UI enhancements and a new opt-in text message alert system which reduced unnecessary student interactions with the Registration team by about 70% in a year. Of this experience was born a passion for using data to solve problems.

Today, I work as a data analyst for a pharmacy benefit consulting firm managing over $100 billion in total drug spend. I spend most of my time using SQL to query our massive claims database for insights and developing savings, projection, and financial models among other ad hoc requests.

This repository serves as a platform to share my projects, showcase my skills, and track my progress in the world of data analytics.


## **Table of Contents**

- [About](#about)
- [Porfolio Projects](#portfolio-projects)
  - [Data Professionals Job Survey](#data-professionals-job-survey)
  - [NBA Statistics](#nba-statistics)
  - [NBA.com Web Scraper](#nbacom-web-scraper)
  - [Sales Dashboard](#sales-dashboard)

 

## **Portfolio Projects**


### **Data Professionals Job Survey**

**Project:** [Data Professionals Job Survey - Power BI](https://app.powerbi.com/view?r=eyJrIjoiMGQ3OWFiNjYtOGJmZC00Yzc2LTg0NjAtNTA0NmE3NTE4MWUwIiwidCI6ImMyMjhlNzY3LTA3YzQtNDdkMC05MWUzLTg3OGRiYjY5ZmE5MCJ9&embedImagePlaceholder=true)

**Description:** This project derives from a survey taken among data professionals around the world with hundreds of responses. Questions included age, sex, country, ethnicity, and other demographics, along with career-oriented questions like estimated salary ranges, work/life balance satisfaction, preferred programming language, and more.

**Skills:** Data collection, data cleaning, dashboard creation, exploratory analysis, qualitative analysis

**Technology:** Power BI, Excel

**Results & Conclusions:** More insights could be added to this project soon as there is much to be unpacked from the survey results. One insight was that, of the responders, men and women typically made about the same amount of money on average. Also, both age and education (two factors assumed to play major roles in salary growth) did not hold near as much weight as I would have thought without having done such an analysis. One last conclusion is that Python appears to be far and away the most popular programming language used around the world among this sample of data professionals.


### **NBA Statistics**

**Project:** [NBA Player Dashboard - Power BI](https://app.powerbi.com/view?r=eyJrIjoiYWNlZGE2YmQtNWM5MC00MjdhLWIwMzUtNTk2NDNhZGVmNjllIiwidCI6ImMyMjhlNzY3LTA3YzQtNDdkMC05MWUzLTg3OGRiYjY5ZmE5MCJ9)

**Description:** This project shows an NBA player dashboard using 10 years of NBA data straight from the official website. In addition to the typical stats you might find on a project like this, I decided to take a shot (pun intended) at my own version of a Player Efficiency Rating. I don’t like that almost 500 players in the League are differentiated by no more than about 30 points. So, I created a “Contribution Rating” which incorporates several per-minute stats, with extra weight placed on +/- and minutes per game.

**Skills:** Web scraping, dashboard creation, exploratory analysis, predictive analysis

**Technology:** Power BI, Excel, Python

**Results & Conclusions:** The Contribution Rating increases the spread of the widely-known PER from ~30 points to ~75, providing more accute visibility in differences between players' individual production.


### **NBA.com Web Scraper**

**Project:** [NBA.com Web Scraper - Sublime](https://github.com/Cody-Graham/My-Data-Portfolio/blob/main/NBA_Stats_Web_Scraper.sublime-workspace)

**Description:** In the midst of working on the NBA Player Dashboard, this project was born out of an attempt to connect a dataset to my dashboard that would automatically update each day as the NBA season progressed.

**Skills:** Web scraping, data cleaning

**Technology:** Python, Sublime Text

**Results & Conclusions:** The web scraper is functional which is a huge success given it was my first one. However, NBA.com seems to be very strict on allowing frequent web requests to pull JSON data, and the data available on their website is not available for download. So using the web scraper to pull 25 seasons of data may throw an error.


### **Sales Dashboard**

**Project:** [Sales Dashboard - Tableau Public](https://public.tableau.com/app/profile/graham.analytics/viz/SalesDashboard_16736662040210/ServiceSales)

**Description:** In this project, I transformed over 20 years of sample sales data for a service-based company into an interactive, quick-glance dashboard. The dashboard allows for exploratory analysis, customer retention, and easy performance tracking.

**Skills:** Data collection, data cleaning, dashboard creation, exploratory analysis, client relations

**Technology:** Tableau Public, Excel

**Results & Conclusions:** As seen in the dashboard itself, it was determined that one of the service categories was being sold for well-under market value, and in subsequent years, aggressive pricing adjustments are made. The end result is a 35% increase in revenue for that service category.

[Back to Top](#cody-graham---data-analysis-portfolio)
