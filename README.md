# Analysis of how Bikesharing Data is Affected by Weather and Time
Vera Kong and Nicole Danuwidjaja

Professor Caglar Yildirim - DS3000

[Final Report](https://github.com/VKong6019/ds3000-F20/blob/main/DS3000_FP4_Section1_Group15.ipynb)
[Group Presentation](https://www.youtube.com/watch?v=lWBLmwkWCJM)

### Executive Summary
Cities are faced with an increase in usage of bike-sharing programs as such technology is becoming readily available. Bike programs provide more people the opportunity to ride a bike, along with providing health and environmental benefits. To best understand how these programs can be best improved for maintenance and accessibility, this project will analyze the relationships between ride-sharer behavior and the weather, particularly in the city of Boston and their Bluebikes program.

This research project will identify the main feature variables and target variables from datasets pulled from the public Bluebikes data as well as from Boston weather. The datasets are wrangled and cleaned in order to perform data analysis. The project uses a predictive model using machine learning techniques to apply algorithms on the cleaned datasets.

Through this research project, we have identified that there is a strong direct correlation with the number of bikesharers and weather.

### Problem Statement
The primary goal of this project is to determine the number of bike-share users on any given day at a specific hour. Bike-sharing programs worldwide have seen a significant increase in the number of bicycles used across numerous cities, with the number of participants varying based on certain conditions (e.x. time of day, weather, or holiday). Since this usage may vary city by city, we want to try to focus on a single city, like Boston and its BlueBikes program. In this project, we will analyze bicycle data from bike-sharing programs to visualize the trip frequency, duration, types of users, and popular areas of interest. We hope to learn more about how bike-sharing programs can impact city infrastructure and safety for pedestrians and cyclists. Furthermore, we aim to utilize a supervised learning approach along with a few machine learning algorithms to better understand the correlation between time/weather conditions and bike-sharing usage.

### Predictive Model
The predictive model will determine the total number of bikeshare users on a given day at a specific hour. This will also be based on the time of year, day of week, and weather since those are key factors in swaying users to participate in a bike-sharing program.

We believe that for the purposes of this report, the data provided from bike-sharing users as well as Boston weather will help provide interesting insights into how these factors can affect the number of people who use bikes.
We will use the Multiple Linear, Ridge, Lasso, and Support Vector Machine regression models since those are the popular regression algorithms used and based on previous performance/accuracy. Moreover, our model will contain multiple features that will contribute to the predictive output, so it is important that we at least include the Multiple Linear Regression in our findings.

### Algorithms
We compared and contrasted four different types of regression algorithms: Multiple Linear, Ridge, Lasso, and Support Vector Machine. Through our project, we determined that both Multiple Linear and Ridge showed the highest performance, as they were able to achieve an exact fit for all four cases: all features with and without weather, and selected features with and without weather. 
For our predictive model, we believe that both Multiple Linear and Ridge regression will provide highly accurate results for our research purposes to determine the total number of bikeshare users on a given day at a specific hour. In our hyperparameterized tuning, we took a closer inspection of the Ridge algorithm and determined that, after finding the best alpha value, the R-squared values calculated have a correlation strength of 99.99%, and show a high performance for our datasets.
All of the algorithms we performed found significance in the correlation of our feature variables and target. Thus, without a doubt, we have identified a strong correlation within our data.

### Next Steps
This research project encourages future studies for more applications in improving bikesharing programs in Boston and other similar cities. By applying machine learning to existing data, researchers will be able to better understand human behavior within cities and how people interact with public transportation programs. In an effort to further support the environment by reducing traffic congestion and pollution, applying such research knowledge into expanding these programs and encouraging more people to share public bikes through the year can benefit our communities.

Future applications beyond this research project include using predictive behavior to determine which stations would be most likely to be empty or full or understanding how certain demographics engage with bike-sharing programs. Data analysis could also be expanded to include crime data or traffic incidents to better inform bike-sharers of potential danger zones.
