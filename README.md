# CarPricePrediction

## Problem Statement

**Project Overview:**

In the automotive industry, determining the price of a car involves various factors, such as brand reputation, car features, horsepower, and fuel efficiency. Car price prediction is a crucial application of machine learning. This project is designed to help you learn how to build a model for car price prediction.


**Key Objectives:**
-Explore the factors affecting car prices.
-Create a machine learning model to predict car prices.
-Gain valuable experience in the field of machine learning and automotive pricing.

**Goal:** Create a machine learning model that forecasts auto prices by taking into account a number of influencing factors.

 **Why Predict Car Prices?**  Numerous factors, such as features, horsepower, fuel efficiency, and brand reputation, affect car prices.  Accurate price predictions can be obtained from machine learning models.

 **Important Tasks:**

 1. **Data Collection:** Compile information on different car characteristics and the associated costs.
 2. **Preparing the data for modeling:** Clean, transform, and get the data ready.
 3. **Feature Engineering:** Determine which features are most crucial for predicting prices.
 4. **Model Building:** Construct a machine learning model that can forecast the cost of automobiles.
 5. **Model Evaluation:** Use the proper metrics to evaluate the model's performance and accuracy.
 6. **Deployment:** Provide the trained model for predicting auto prices.

**Advantages:**  We will learn a lot about data analysis, machine learning, and the automotive sector by finishing this project.  Additionally, we will have a working model for predicting car prices, which will be helpful for future pricing decisions.

## Results

The R2 score is the main evaluation metric that I have chosen for the Car Price Prediction model. The final list is obtained by eliminating the overfitted models that have negative accuracy values and MSE, R2, and Adjusted R2 scores for training at 100%.

| Sl. No. | Regression Model      |   R2 Train (%) |   R2 Test (%) |
|:--------|:--------------------------|---------------:|--------------:|
|    1    | Linear Regression         |       64.21  |      49.24 |
|    2    | Linear Regression tuned       |       64.21  |      49.24 |
|    3    | Lasso Regression tuned       |       63.62 |      49.57 |
|    4    | Ridge Regression         |       64.19 |      49.36 |
|    5    | Ridge Regression tuned        |       63.92 |      50.22 |
|    6    | Decision Tree tuned         |       76.00 |      70.37 |
|    7    | Random Forest         |       98.61 |      93.05 |
|    8    | Random Forest tuned        |       77.10 |      73.71 |
|    9    | Gradient Boosting Regressor         |       98.78 |      90.47 |
|    10    | Gradient Boosting Regressor tuned        |       96.11 |      88.24 |

## Conclusion
The goal of this project is to use machine learning to forecast car prices by examining the complex dynamics of the automotive industry.  We find important insights and choose a reliable model for precise price prediction by examining a number of variables, including fuel type, seller type, and transmission.

 **Important Takeaways:**

 -An overview of the most popular car models on the market is given by the fact that the "city" model is the best-selling vehicle, followed by the "corolla altis," "verna," "fortuner," and "brio."

 -The most popular year for car purchases was 2015, which saw the most purchases, followed by 2016 and 2014.

 -Fuel preference among buyers is demonstrated by the fact that "Petrol" is the most common fuel type for cars in the dataset, outperforming "Diesel" and "CNG."

 -The role of dealerships in the automotive industry is highlighted by the fact that most cars are sold through them.

 -'Automatic' transmission cars are greatly outnumbered by'manual' transmission cars, indicating consumer preferences for transmissions.

 -'First Owner' cars typically fetch a higher 'Selling_Price,' whereas 'Second' or 'Third Owner' cars tend to be less expensive.

 -The 'Selling_Price' of 'Diesel' cars is typically higher than that of 'Petrol' or 'CNG' cars, highlighting the impact of fuel type on automobile pricing.

 -'Dealer' sellers typically raise their prices compared to 'Individual' sellers, demonstrating how seller type affects pricing.

 -Due to consumer preferences, cars with "automatic" transmissions are generally more expensive than those with "manual" transmissions.

 -Car prices are influenced by the number of "owners," with "First Owner" vehicles costing more than "Second" or "Third Owner" vehicles.

With 98% training accuracy and 93% testing accuracy, the Random Forest model demonstrated remarkable accuracy, making it a good option for predicting car prices.

From the standpoints of exploratory data analysis and machine learning models, the insights offer a comprehensive understanding of the factors influencing auto prices. The accuracy of the Random Forest model highlights its potential for useful applications in the automotive industry.

This project is an important step in the field of data science and machine learning since it has not only given us useful data science skills but also expanded our knowledge of car pricing.











