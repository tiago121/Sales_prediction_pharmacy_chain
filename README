# Sales_prediction_pharmacy_chain

![image](https://user-images.githubusercontent.com/88745881/207366040-0f610dd8-1dc4-470c-9b8e-d0d62ad52105.png)


#### Created by by Tiago Araujo

# Description

This project aims to predict the sales of multiple pharmacies using Linear Regression.

# 1. Business Problem

A pharmacy chain wants to modernize its stores by implementing a home delivery service in all of its locations. However, the operation cost is high, and the main challenge is to determine if the stores will generate enough revenue in the next 6 months to cover the renovation costs and still be profitable.

# 2. Solution Strategy

**Step 01. Data Description and Data Cleaning:**

The data was obtained from the Kaggle platform and includes information about the stores, competitors, and seasonal events (such as promotions and holidays).
Link: https://www.kaggle.com/c/rossmann-store-sales

Objective: Gain a clear understanding of the data and prepare the dataset for further analysis.

Process: Renaming and adjusting variable names and types; filling in missing data; compiling information from numerical and categorical variables.


**Step 02. Feature Engineering:**

Objective: Enhance the information available in the dataset and make it easier to interpret for the models.

Process: Transforming temporal variables to indicate time since specific events and renaming categorical variables for better interpretation during the Exploratory Data Analysis (EDA) phase.

**Step 03. Data Filtering:**

Objective: Focus the analysis on relevant data to understand the sales phenomenon.
Process: Selecting data only for open stores with sales; removing irrelevant features.

**Step 04. Exploratory Data Analysis (EDA):**

Objective: Explore the data to gain insights from the data.
Process: Conducting univariate, bivariate, and multivariate analyses, using tables and graphs, to understand the relationships between variables.

**Step 05. Data Preparation:**

Objective: Format the data to be compatible with the model training process.
Process: Scaling, encoding, and transforming variables, including handling temporal data.

**Step 06. Feature Selection:**

Objective: Select the most important features for the model using the Boruta algorithm.
Process: Splitting the data into training and testing sets based on temporal logic; employing the Boruta algorithm and insights from EDA to select features.

**Step 07. Model Training and Testing:**

Objective: Train various regression models and evaluate their performance.
Process: Applying the training and testing datasets and evaluating the model performance using metrics such as Mean Absolute Error (MAE), Mean Absolute Percentage Error (MAPE), and Root Mean Square Error (RMSE).

**Step 08. Fine-Tuning:**

Objective: Optimize the model parameters to improve its performance.
Process: Using the random search algorithm to optimize the model parameters.

**Step 09. Business Performance Evaluation:**

Objective: Translate the model metrics into business performance for decision-making.
Process: Using the variation in MAE as a kind of "confidence interval" to create business scenarios (pessimistic, realistic, and optimistic).

# Top Insights

1. Stores located closer to their nearest competitors tend to have higher sales.

![image](https://user-images.githubusercontent.com/88745881/207604932-de72ea46-5728-453b-8141-2b685297efe5.png)

2. There is a significant decrease in sales during the first 40 to 50 weeks when consecutive promotions are held.

![image](https://user-images.githubusercontent.com/88745881/207606165-7f20c910-bde2-466a-80cb-87d7a81e916f.png)

3. Active promotions that run for a longer duration result in lower sales (top graphs).

![image](https://user-images.githubusercontent.com/88745881/207606654-c954a5cc-6041-46d9-a00e-57f5395437c3.png)



# 3. Model Evaluation

In the machine learning stage, the ML modeling is performed. Four models were trained using cross-validation:

![image](https://user-images.githubusercontent.com/88745881/207362195-49a621be-b5a9-4aa8-ad8d-f4758d0ddab4.png)

The XGBoost model was chosen for this project as it proved to be the fastest and most efficient algorithm for training and fine-tuning.

# 4. Business Results

Predctions were made for each store, considering different scenarios. It is necessary to analyze each case individually to determine if the renovation is worthwhile, but in general, it is recommended. Here are the predictions for all stores for the next 6 months:
![image](https://user-images.githubusercontent.com/88745881/207363754-482e15f5-6adb-4dce-8b4a-8cf38e57b039.png)


# 5. Conclusions

* Although some stores having considerable errors, almost all of them have errors below 20% (MAPE) in the predictions.
* The scenarios created enable more responsible decision-making: for most stores, investing in the home delivery infrastructure is recommended, as the revenue shows relative predictability, assuming no unexpected events occur.
* Our model is 4x better at predicting revenue compared to the model currently used by the store (average).

# 6. Next Steps

 * Train different models.
 * Deploy the model in production
