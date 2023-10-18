## SpaceX-Falcon9-Landing-Prediction

# Overview
This project aims to create a machine learning pipeline for predicting the successful landing of SpaceX Falcon 9 rocket first stages. The ability to predict whether the first stage will land successfully is crucial for estimating the cost of a rocket launch, as SpaceX's cost advantage largely depends on the reusability of the first stage.

# Methodologies
The project follows the following methodologies:

-> Data Collection through API: We gather data related to SpaceX Falcon 9 launches using relevant APIs.
-> Data Collection with Web Scraping: In cases where API data is insufficient, we employ web scraping techniques to obtain the necessary information.
-> Data Wrangling: We process and clean the collected data to make it suitable for analysis.
-> Exploratory Data Analysis with SQL: We perform preliminary data exploration and analysis using SQL queries.
-> Exploratory Data Analysis with Data Visualization: We visualize the data to gain insights into the factors affecting the success of Falcon 9 first stage landings.
-> Interactive Visual Analytics with Folium: We create interactive visualizations to provide a user-friendly way to explore the data.
-> Machine Learning Prediction: Using machine learning techniques, we build a predictive model to forecast the likelihood of a successful landing.

# Summary of Results
Exploratory Data Analysis Result
Our initial data exploration reveals several key findings:

-> The larger the flight amount at a launch site, the greater the success rate at a launch site. This suggests that launch experience and infrastructure play a significant role in the success of Falcon 9 landings.

-> Launch success rates started to increase in 2013 and continued to improve until 2020. This trend aligns with SpaceX's commitment to reusability and their learning curve over the years.

-> Orbits ES-L1, GEO, HEO, SSO, and VLEO had the highest success rates, indicating that certain orbits are more challenging than others.

-> KSC LC-39A had the most successful launches of any sites, further emphasizing the significance of the launch site in successful landings.

# Interactive Analytics in Screenshots
We provide screenshots and interactive visualizations created with Folium to facilitate data exploration and understanding.

# Predictive Analytics Result
The Decision tree classifier emerges as the best machine learning algorithm for this task. It offers insights into the likelihood of a successful landing for a given Falcon 9 launch. It can be used to estimate launch costs and potentially enable alternate companies to bid against SpaceX for rocket launches.
