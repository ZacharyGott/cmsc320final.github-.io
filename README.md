# Used Vehicle Sales Price Prediction  
_Final Project – CMSC320 (Fall 2025)_  
<br>
Zachary Gottlieb, Kehan Bhati, Joseph Jenkins, Jack Perlman, Simon Benarroch, Aidan Ritta

## Contributions
Zachary:
<br><br>
Kehan:
<br><br>
Joseph:
<br><br>
Jack:
<br><br>
Simon:
<br><br>
Aiden:
<br><br>



## Introduction
&nbsp;&nbsp;&nbsp;&nbsp;Accurately predicting the price of a used car is an important challenge with many complexities. It has great value for both consumers and professional members of the automobile industry. This project focuses on understanding which factors strongly influence the selling price of used cars and on developing a predictive model that can estimate prices based on those factors. Since car purchases are one of the largest financial decisions made by many individuals, accurate pricing is essential for helping consumers avoid overpaying and helping sellers accurately value their vehicles.
<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;The significance of our analysis extends beyond individual transactions; pricing insights can also help dealerships, online marketplaces, and businesses make large-scale decisions. This investigation centers on several key questions: Which characteristics are most strongly correlated with selling price? How accurately does a machine learning model predict used car prices using these features? What patterns about the used vehicle market can be revealed through this analysis? How can these patterns be utilized to benefit both consumers and sellers of the industry? Our project aims to answer these questions through the study of the Vehicle Sales dataset from Kaggle. The predictive model provides key insights which can help anyone improve their decision-making in the used vehicle marketplace.



## Data Curation

## Exploratory Data Analysis

## Primary Analysis

## Visualization

## Insights and Conclusion
&nbsp;&nbsp;&nbsp;&nbsp;Throughout this tutorial, we walked through some stages of data science for creating a machine learning model that accurately predicts the price of a used car. To build the model, we had to learn what features drive the selling prices of used cars. We expectedly proved that the vehicle's age and mileage are inversely correlated with its selling price. In addition to age and mileage, we found that the Market Maker Valuation (MMR) is the single strongest predictor of the car's final sell price. Essentially, the market estimate alone is very accurate, but additional factors like the condition and its age can also affect the final price.

&nbsp;&nbsp;&nbsp;&nbsp;However, the results go beyond simple correlation. We addressed potential overfitting by comparing a Linear Regression model with a Ridge Regression model. The results showed that while a simple linear model captured the bulk of the variance ($$R^2$$ score), the Ridge Regression model predicted the test data marginally better, giving a more robust model that is very generalizable to new data.

&nbsp;&nbsp;&nbsp;&nbsp;Ultimately, this project shows that while used car pricing can seem very volatile, it mostly follows predictable patterns that can be effectively modeled using standard machine learning techniques. The resulting model serves as a viable tool for verifying fair market values, helping reduce the pricing uncertainty for both buyers and sellers.
