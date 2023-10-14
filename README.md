# Olympics EDA Web Application

![premium_photo-1666107278222-862cd7890c5e](https://github.com/Md-Kaif-Tahir/Laptop-price-prediction-model./assets/110182266/4e318210-5ac8-4c33-a5fc-8e477ab17079)

Overview
- Welcome to the Olympics Exploratory Data Analysis (EDA) Web Application! This application provides a comprehensive analysis of Olympic Games data, offering insights into medal tallies, overall trends, country-wise performances, and athlete-wise achievements.

 Sections:
1. Medal Tally:
- View the medal count for each country, filtered by year.
- Customize your view by selecting a specific country and/or year.
- Gain insights into a country's overall performance or focus on a specific Olympic year.
2.Overall Analysis:
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

- [Business Problem](#business-problem)
- [Methods](#methods)
- [Tech Stack](#tech-stack)
- [Quick Glance at the Result](#quick-glance-at-the-result)
- [Lessons Learned and Recommendations](#lessons-learned-and-recommendations)
- [Limitations and What Can Be Improved](#limitations-and-what-can-be-improved)
- [Run Locally](#run-locally)
- [Explore the Notebook](#explore-the-notebook)
- [App Deployed on Streamlit](#app-deployed-on-streamlit)
- [Blog Post](#blog-post)

## Business Problem

In the ever-evolving laptop market, businesses face the challenge of predicting the prices of laptops accurately. This is crucial for several reasons, including optimizing inventory management, setting competitive pricing strategies, and meeting customer expectations. An inaccurate prediction could lead to overstocking, tying up valuable resources, or underpricing, resulting in potential revenue loss. Understanding the factors influencing laptop prices, such as specifications, operating systems, and brand preferences, is essential for businesses to make informed decisions and stay competitive in the dynamic market. Developing a reliable prediction model for laptop prices is not just a statistical challenge; it directly impacts the bottom line and overall success of businesses operating in the laptop retail space.

## Methods

- Data preprocessing
- Exploratory data analysis
- Feature engineering
- Modelling
  

## Tech Stack

- Python (preparation of the model)
- Streamlit (interface for the model)

## Quick Glance at the Result

a brief summary of the project's results.

### 1. Distribution of the price  
![image](https://github.com/Md-Kaif-Tahir/Laptop-price-prediction-model./assets/110182266/ad30139f-3128-47ea-b2d8-29cc7eda8387)

Observation:
- laptop price estimates spanning from Rs.9,270 to Rs.3,24,954, with a notable concentration within the range of Rs.30,000 to Rs.1,50,000. This distribution is characterized by a right-skewed pattern, indicative of a prevalence of laptops within the specified moderate to high-value spectrum.

### 2. Distribution of the laptop on basis of the brand
![image](https://github.com/Md-Kaif-Tahir/Laptop-price-prediction-model./assets/110182266/40ad3289-1344-45e1-add3-ca366b03cea9)

Observation
- The dataset prominently features three leading laptop brands: Dell, Lenovo, and HP, exhibiting the highest occurrence. Subsequently, Asus, Acer, MSI, and Toshiba follow suit in descending order, with counts surpassing 50. Beyond these major players, a multitude of other brands registers in the dataset, each with a count below 50, as illustrated in the bar chart where brand names are represented along the X-axis and the corresponding laptop counts are depicted along the Y-axis.

### 3. Price vs brand relationship
![image](https://github.com/Md-Kaif-Tahir/Laptop-price-prediction-model./assets/110182266/741da932-0df3-4939-9fa0-8d48b45fa10b)

Observation
- Notably, Apple MacBooks consistently appear with prices below the Rs.1,00,000 thresholds in the dataset. This revelation is surprising, considering the prevalent trend of Apple products in India typically falling within the upper price range, often exceeding Rs.1,00,000. However, it's important to clarify that the observed lower prices in the dataset are attributed to older models of MacBooks, which are reflective of historical pricing. In contrast, Razer laptops stand out with a notable prevalence of high-cost models, often associated with gaming configurations.
-	Meanwhile, the trio of Dell, Lenovo, and HP, collectively constituting a substantial portion of sales, share a relatively similar pricing bracket. Other brands within the dataset fall within the spectrum, bridging the gap between the comparatively lower-priced Apple MacBooks and the higher-end Razer laptops, forming a diverse range.

### 4 Count of the type of laptops
![image](https://github.com/Md-Kaif-Tahir/Laptop-price-prediction-model./assets/110182266/0e00938a-0f9e-4cf0-ab92-9368bfa1eb7b)

Observation 
-	The dataset predominantly features over 700 instances of "Notebook" laptops, surpassing "Gaming" and "Ultrabook" categories, each with around 200 occurrences. A notable contrast exists, particularly with a 500-instance difference between "Notebook" and "Gaming"/"Ultrabook," highlighting significant user preferences. 
-	Conversely, "2-in-1 Convertible," "Workstation," and "Netbook" exhibit lower counts, with the latter two falling below 100 occurrences. The "2-in-1 Convertible" category, though less frequent than "Notebook," still stands at approximately 100 instances, suggesting a moderate presence.

### 5 Prices of the different type laptop
![image](https://github.com/Md-Kaif-Tahir/Laptop-price-prediction-model./assets/110182266/c22aea49-88b0-4b7e-9141-5c03e11bfb16)

Observation
- In terms of pricing, Ultrabooks and Gaming laptops exhibit a close resemblance, with Ultrabooks priced at approximately Rs. 80,000 and Gaming laptops hovering around Rs. 85,000.
- Notably, the Workstation category stands out as the most expensive, commanding a premium price point. The 2-in-1 Convertible laptops are positioned around Rs. 60,000, while Notebooks and Netbooks emerge as the more budget-friendly options, ranging from Rs. 30,000 to Rs. 40,000, with Netbooks representing the lower end of this spectrum. This diversity in pricing underscores the wide range of options available in the laptop market, catering to varying budget considerations and preferences.
-	The error bars also show that some types of laptops have more consistent prices than others. For example, the error bar for the Ultrabook laptop is relatively small, which means that most Ultrabook laptops have similar prices. On the other hand, the error bar for the Workstation laptop is relatively large, which means that there is a wide range of prices for Workstation laptops. This could indicate that some types of laptops are more standardized than others, or that some types of laptops have more diverse options and preferences than others.

### 6 distribution of laptop on basis of its screen size
![image](https://github.com/Md-Kaif-Tahir/Laptop-price-prediction-model./assets/110182266/134ff0a5-6089-45ab-8f7f-672a60a327ed)

Observation 
-	The graph shows the relationship between the density of the laptops and its length in inches. The density is measured in units of mass per unit volume, such as grams per cubic centimetre.
-	The graph has a bell-shaped curve, which means that the density follows a normal distribution. This means that most of the values are clustered around the mean or average, and the values become less frequent as they deviate from the mean.
-	The graph has a peak at around 16 inches, which means that this is the mode or the most common value of the screen size. The density at this point is about 1.5.
- The graph has a smaller peak at around 14 inches, which means that this is another common value of the screen size, but less frequent than 16 inches. The density at this point is about 1.25.
-	The graph has another peak around 17 inches, which means that this is another common value of the screen size. The density of this point is about 0.20

## Lessons Learned 

-	A substantial proportion of laptops, totalling around 1000 units, do not feature touchscreen functionality, while a more modest count of 200 laptops incorporates this touch-enabled capability.
-	Intel Core i7 is the most dominant, featured in about 500 laptops, closely followed by i5 with 400. Intel Core i3 has a similar count around 150, while AMD processors are less represented, with fewer than 100 laptops.
-	AMD graphics cards stand out as the most budget-friendly option in the market. They are known for providing a good budget experience. However, it's worth mentioning that laptops with AMD processors are not as common; the market is largely dominated by Intel and Nvidia. AMD tends to have a stronger presence in the desktop market.

## Limitations and What Can Be Improved

- The dataset's small size, approximately 1000 rows, resulted in notable variance, particularly in CPU and GPU models
- To mitigate this, grouping the rows by brand instead of model was implemented; however, a larger dataset would have allowed for a more granular analysis at the model level.
- Hyperparameter tuning

## Explore the Notebook

[Link to Kaggle Dataset](https://www.kaggle.com/datasets/muhammadusman996/ozlaptop)

## App Deployed on Streamlit

![ezgif com-video-to-gif](https://github.com/Md-Kaif-Tahir/Laptop-price-prediction-model./assets/110182266/4c6a3684-0434-458c-a530-778b41a1c780)

## Blog Post

- Currenly working on the blog
