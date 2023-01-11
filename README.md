# nosql-challenge
Module 12 No-SQL challenge for UCI Data Analytics Bootcamp Vincent Passanisi

# mars_news_challenge
Module 11 Challenge for Data Analytics Bootcamp

Vincent Passanisi

Due January 5, 2023 / Submitted January 7, 2023

# **Introduction**

This challenge required two deliverables. First, a notebook that scraped a Mars News website for the article titles and preview text. Once the scraping was accomplished, it was saved into a python list. The second deliverable was a notebook that scraped a website with a table that had temperature and atmospheric pressure data collected by Curiosity, a mars-rover vehicle, roughly the size of a car. The data in the table was collected from 8/16/2012 through 02/27/2018, a period of about five-and-a-half years. The table was scraped and a dataframe created from which graphs were produced to display the minimum temperatures and atmospheric pressure grouped by month.

# **Files**

In the folder *mars_web_analysis* are the completed challenge files.

* *NoSQL_setup_final.ipynb* - my jupyter notebook with the set-up script for the NoSQL challenge.
* *NoSQL_analysis_final.ipynb* - my jupyter notebook with the analysis script for the NoSQL challenge, and answers to questions
* *part_2_mars_weather_final_bs* - I created a second notebook that used pd.read.html to collect the table data into a dataframe instead of looping through the beautiful soup object
* *Resources* folder with .csv files of saved databases.
    * mars_facts.csv
    * martian_min_pressure.png
    * martian_min_temp_total.png
    * martian_min_temp.png

# **Results**

*Deliverable 1: NoSQL Setup*


    ]

*Deliverable 2: NoSQL Analysis*




# **Comments and Thoughts**

I learned a lot from this challenge. My biggest struggle was getting my table into a dataframe using a loop. It was super easy to just use the pd.read.html, but I struggled to get my loop right. Our TA Grace was super helpful, and gave me some guidance that totally opened my eyes. She shared a snippet of code that not only helped me with the challenge, but completely opened my eyes to loops and python lists. All of a sudden it came to me, and I totally got it. Everything from the beginning of class made so much more sense. I think I'm going to struggle far less with those loos in the future. Thank you Grace!!!!!
