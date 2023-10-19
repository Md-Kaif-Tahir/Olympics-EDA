# Olympics EDA Web Application

![image](https://github.com/Md-Kaif-Tahir/Olympics-EDA/assets/110182266/60539580-d9e3-485b-94d4-553a6eb2579b)


Overview
- Welcome to the Olympics Exploratory Data Analysis (EDA) Web Application! This application provides a comprehensive analysis of Olympic Games data, offering insights into medal tallies, overall trends, country-wise performances, and athlete-wise achievements.

 Sections:
1. Medal Tally:
- View the medal count for each country, filtered by year.
- Customize your view by selecting a specific country and/or year.
- Gain insights into a country's overall performance or focus on a specific Olympic year.
2. Overall Analysis:
- Explore key statistics, including the number of editions, host cities, sports, events, athletes, and participating nations.
- Visualize the growth of participating nations, events, and athletes over the years through interactive line charts.
- Delve into a heatmap showcasing the number of events across various sports over time.
- Identify the top-performing athletes in each sport.
3. Country-wise Analysis:
- Select a country to view its medal tally over the years through an interactive line chart.
- Explore a heatmap illustrating the country's success in different sports across various Olympic editions.
- Discover the top 10 athletes from the selected country.
4. Athlete-wise Analysis:
- Examine the distribution of ages among athletes, including gold, silver, and bronze medalists.
- Analyze the age distribution of gold medalists across various sports.
- Explore a scatter plot depicting the relationship between height and weight of athletes, with medal information.
- Track the participation trends of men and women over the years.

## Authors

- [Mohammad Kaif Tahir](https://github.com/Md-Kaif-Tahir)

## Table of Contents

## Table of Contents

- [Methods](#methods)
- [Tech Stack](#tech-stack)
- [Quick Glance at the Result](#quick-glance-at-the-result)
  - [1. Medal Tally](#1-medal-tally)
  - [2. Overall Analysis](#2-overall-analysis)
    - [Growth of Participating Nations](#growth-of-participating-nations)
    - [Number of Events Over Time](#number-of-events-over-time)
    - [Number of Athletes Over Time](#number-of-athletes-over-time)
    - [Number of Events for Each Sport](#number-of-events-for-each-sport)
    - [Top-Performing Athletes](#top-performing-athletes)
  - [3. Country-wise Analysis](#3-country-wise-analysis)
    - [USA Medal Tally Over the Years](#usa-medal-tally-over-the-years)
    - [Excellence in Sports Over Time (USA)](#excellence-in-sports-over-time-usa)
    - [Top 10 Athletes of USA](#top-10-athletes-of-usa)
  - [4. Athlete-wise Analysis](#4-athlete-wise-analysis)
    - [Excellence in Sports Over Time (Athletes)](#excellence-in-sports-over-time-athletes)
    - [Relationship Between Weight and Height](#relationship-between-weight-and-height)
    - [Gender-wise Participation Over the Years](#gender-wise-participation-over-the-years)
- [Lesson-learned](#Lessons-Learned)
- [Authors](#authors)
- [Explore the Notebook](#explore-the-notebook)
- [App Deployed on Streamlit](#app-deployed-on-streamlit)
- [Blog Post](#blog-post)


## Methods

- Data preprocessing
- Exploratory data analysis
- Web Application using stramlit 
  

## Tech Stack

- Python (preparation of the Web Application)
- Streamlit (interface for the Web Application)

## Quick Glance at the Result

### 1. Medal Tally 
![image](https://github.com/Md-Kaif-Tahir/Olympics-EDA/assets/110182266/17ca4397-6829-4112-91ec-d624386aea59)

- The sidebar lets you choose various sections, and you can further narrow down your selection by picking a specific "Year" and "Country."
- The table shows the overall tally of medals won by different countries in the Olympic Games.
- The table has five columns: region, gold, silver, bronze, and total. The region column shows the name of the country, and the other columns show the number of medals of each type and the total number of medals.
- The table is sorted by the total number of medals won by each country, from highest to lowest.

### 2. Overall Analysis
![image](https://github.com/Md-Kaif-Tahir/Olympics-EDA/assets/110182266/f17223ee-7ddf-47bb-b91c-8a338ecdeaaa)

- The table shows some statistics about the Olympic Games, such as the number of editions, hosts, sports, events, nations, and athletes.
- The second row shows that there have been 28 editions of the Olympic Games, with 23 different hosts and 52 different sports.
- The fourth row shows that there have been 651 events in the Olympic Games, with 206 participating nations and 116122 competing athletes.

![image](https://github.com/Md-Kaif-Tahir/Olympics-EDA/assets/110182266/cd8d5d28-b446-4359-8150-066f63da15e4)

- The graph shows how the number of countries that participated in the Olympic Games changed over the years from 1900 to 2000.
- The graph shows a general increase in the number of countries over time, which means that the Olympic Games became more popular and inclusive for different regions of the world.
- The graph also shows a slight dip around 1940, which might be related to the World War II that disrupted many countries and events.
- The graph reaches the highest point around 2000, with about 150 countries. This shows that the Olympic Games reached a global scale and attracted many diverse nations.

![image](https://github.com/Md-Kaif-Tahir/Olympics-EDA/assets/110182266/266a55a6-4bc7-4e46-ba6f-a7b4cf01ae0d)

- The graph shows how the number of events that were held in the Olympic Games changed over the years from 1900 to 2000.
- The graph shows a steady increase in the number of events over time, which means that the Olympic Games became more diverse and competitive for different sports and disciplines.
- The graph has a sharp increase in the number of events between 1940 and 1960, which might be related to the post-war recovery and the expansion of the Olympic movement to new regions and countries.
- The graph has a gradual increase in the number of events between 1960 and 2000, which might reflect the stabilization and consolidation of the Olympic Games as a global event.


![image](https://github.com/Md-Kaif-Tahir/Olympics-EDA/assets/110182266/e4e458f0-89e9-4e49-8bdb-0254af8bb4f4)

- The graph shows how the number of athletes that participated in the Olympic Games changed over the years from 1900 to 2000.
- The graph shows a general increase in the number of athletes over time, which means that the Olympic Games became more attractive and accessible for different people and countries.
- The graph has some fluctuations in the number of athletes, which might be related to the historical events and circumstances that affected the Olympic Games, such as wars, boycotts, or pandemics.
- The graph reaches the highest point around 2000, with about 10k athletes. This shows that the Olympic Games reached a peak of participation and popularity.

![image](https://github.com/Md-Kaif-Tahir/Olympics-EDA/assets/110182266/1e3f3fe2-3bb5-4cce-8022-da4d50322411)

- The graph shows how the number of events for each sport changed over time from 1900 to 2000.
- The graph is a horizontal bar graph with a black background and different shades of purple and orange for the bars.
- The graph has a color gradient on the right side that shows the range of colors used for the bars. The colors indicate the year of the edition, with darker colors for earlier years and lighter colors for later years.
- The graph shows that some sports have been consistent in the number of events, such as athletics, cycling, and gymnastics. These sports have been present in almost every edition of the Olympic Games.
- The graph also shows that some sports have been variable in the number of events, such as shooting, wrestling, and fencing. These sports have had changes in the number of events due to different factors, such as popularity, rules, or availability.
- The graph also shows that some sports have been new or recent in the number of events, such as triathlon, taekwondo, and badminton. These sports have been introduced or expanded in the Olympic Games in the late 20th century.

![image](https://github.com/Md-Kaif-Tahir/Olympics-EDA/assets/110182266/53dca71d-2fe1-423d-89a7-374b9cc4f548)

- The table shows the rank, name, sport, and country of the most successful athletes in the Olympic Games.
- The table has a dropdown menu to select a sport and filter the results accordingly.
- The table has 4 columns and 12 rows. The first row is the header row and it has the labels “Overall”, “Name”, “Sport”, and “Country”.
- The table is sorted by the “Overall” column, which is the rank of the athlete based on the number of medals wons.
- The table has hyperlinks for the athletes’ names, which presumably lead to their individual profiles with more details.
- The table has athletes from various sports and countries, such as swimming, gymnastics, athletics, USA, Russia, and Germany.

### 3. Country-wise Analysis

![image](https://github.com/Md-Kaif-Tahir/Olympics-EDA/assets/110182266/d66e4880-5d5f-46a6-9077-5737b68df8a7)

- The graph and charts can be changed by selecting the country from the dropdown
- The main content of the webpage is a line graph titled “USA Medal Tally over the years”. The graph shows how many medals the USA won in the Olympic Games from 2000 to 2020.
- The graph shows that the USA had a peak in the number of medals won in 2004, with about 260 medals. The graph also shows that the USA had a decline in the number of medals won in 2016 and 2020, with about 120 and 110 medals respectively.
- The graph might suggest that the USA’s performance in the Olympic Games has been affected by various factors, such as competition, politics, or health. The graph might also indicate that the USA needs to improve its strategies and preparations for future Olympic Games.

![image](https://github.com/Md-Kaif-Tahir/Olympics-EDA/assets/110182266/5a4a63bb-161e-44b9-a5cb-67b9b2d38450)

- The heat map shows the level of excellence of the USA in each sport over time from 1960 to 2012.
- The heat map is a grid of rectangles, each representing a sport. The x-axis shows the years and the y-axis shows the sports.
- The heat map has a color scale that shows the level of excellence in each sport in each year. The darker the color, the higher the level of excellence.
- The heat map shows that the USA has been consistent in some sports, such as basketball, swimming, and boxing. These sports have been mostly dark-colored, which means that the USA has been very successful in them.
- The heat map also shows that the USA has been improving in some sports, such as gymnastics, volleyball, and tennis. These sports have been getting darker over time, which means that the USA has been increasing its excellence in them.
- The heat map also shows that the USA has been declining or struggling in some sports, such as shooting, wrestling, and sailing. These sports have been getting lighter over time, which means that the USA has been losing its excellence in them.

![image](https://github.com/Md-Kaif-Tahir/Olympics-EDA/assets/110182266/db5ea743-6601-48f9-8f45-2c6fca141d9b)

- The table shows the name and the sport of the top 10 athletes of USA in the Olympic Games.
- The table has two columns and 12 rows. The first row is the title “Top 10 athletes of USA” and the second row is the header row with the labels “Name” and “Sport”.
- The table is sorted by the athlete’s name in alphabetical order.
- The sports represented in the table are swimming, shooting, athletics, and basketball. These are some of the sports that USA excels in, as shown by the heat map.
- The athletes in the table are some of the most successful and decorated Olympians of all time, with many medals and records to their names. For example, Michael Phelps is the most decorated Olympian ever, with 28 medals, 23 of them gold.


### 4. Athelete wise Analysis

![image](https://github.com/Md-Kaif-Tahir/Olympics-EDA/assets/110182266/0d5e6bb7-9070-4719-a501-e4b3fa89cd5b)

- The graph is a grid of rectangles, each representing a sport. The x-axis shows the years and the y-axis shows the sports.
- The graph has a color scale that shows the level of excellence in each sport in each year. The darker the color, the higher the level of excellence.

![image](https://github.com/Md-Kaif-Tahir/Olympics-EDA/assets/110182266/9199404b-1c3d-49f8-a215-6e7d781408a3)
- The graph shows the relationship between the weight and the height of the Olympic athletes, and how it differs by the type of medal they won.
- The graph is a scatter plot with data points in the form of circles and crosses. The x-axis shows the weight and the y-axis shows the height of the athletes.
- The graph has a color scheme that shows the type of medal won by the athletes. The colors are explained by the legend on the right side of the graph. The legend shows that the colors are orange for bronze medalists, green for silver medalists, red for gold medalists, and black for non-medalists.
- The graph is interactive, as indicated by the “Select a Sport” dropdown menu above the graph. The user can select a sport and see how the data points change accordingly.
- The graph shows that there is a positive correlation between weight and height for most athletes, which means that heavier athletes tend to be taller and vice versa.
- The graph also shows that there is a variation in weight and height among different types of medalists, which might reflect the different physical requirements and advantages for different sports and events. For example, gold medalists tend to be heavier and taller than silver and bronze medalists, which might suggest that they have more strength and power.

![image](https://github.com/Md-Kaif-Tahir/Olympics-EDA/assets/110182266/2c72e1c3-a279-4ed3-8b03-8522e722c8e1)

- The graph shows the number of participants in thousands for men and women over the years from 1990 to 2009.
- The graph is a line graph with two lines, one for men and one for women. The x-axis shows the years and the y-axis shows the number of participants in thousands.
- The graph has a color scheme that shows the gender of the participants. The colors are explained by the legend on the top right corner of the graph. The legend shows that the colors are blue for men and orange for women.
- The graph shows that there is a gap between the number of participants for men and women, which means that there is a gender imbalance in the Olympic Games. The gap is larger in earlier years and smaller in later years, which means that the gender imbalance has been reducing over time.
- The graph also shows that there is a growth in the number of participants for both men and women, which means that the Olympic Games have been becoming more popular and inclusive over time. The growth is faster for women than for men, which means that women have been gaining more opportunities and recognition in the Olympic Games.

## Lessons Learned 

- The Olympic Games are fascinating and multifaceted, involving history, geography, culture, politics, sports, and statistics.
- Over time, they have evolved to become more popular, diverse, inclusive, and competitive across regions, countries, sports, and athletes.
- Challenges like wars, boycotts, pandemics, scandals, and controversies have been part of the Olympic Games' history.
- Various sources, including tables, graphs, maps, and websites, provide information and analysis, aiding in understanding and comparing Olympic Games data and trends.
- The Olympic Games are rich in stories and achievements, showcasing successful athletes, exciting events, memorable moments, and inspiring values.

## Explore the Notebook

[Link to Kaggle Dataset](https://www.kaggle.com/datasets/mohammadkaiftahir/laptop-price-in-india)


## Blog Post

- Currenly working on the blog
