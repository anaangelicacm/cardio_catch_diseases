# Predicting cardiovascular diseases

# 1. Business Problem
Cardio Catch Diseases is a company specialized in detecting heart disease in the early stages. Its business model lies in offering an early diagnosis of cardiovascular disease for a certain price.

Currently, the diagnosis of cardiovascular disease is manually made by a team of specialists. The current accuracy of the diagnosis varies between 55% and 65%, due to the complexity of the diagnosis and also the fatigue of the team who take turns to minimize the risks. The cost of each diagnosis, including the devices and the payroll of the analysts, is around $1,000.00.

The price of the diagnosis, paid by the client, varies according to the precision achieved by the team of specialists.

| Exam Accuracy | Price | Rules | Example |
| --- | --- | --- | --- |
| Above 50% | min $500.00 | +$500 for each additional 5% precision | Precision = 55% -> $1,000.00 |
| Up to 50% | $0.00 | N/A | N/A |

Thus, we see that different values in the exam precision, given by the team of specialists, make the company either have a profitable operation, revenue greater than the cost, or an operation with a loss, revenue less than the cost. This instability of the diagnosis makes the company to have an unpredictable cashflow.

# 2. Business Assumptions

# 3. Solution Strategy
- **Step 1. Data Description:** My goal is to use statistics metrics to identify data outside the scope of business;
- **Step 2. Feature Engineering:** Derive new attributes based on the original variables to better describe the phenomenon that will be modeled;
- **Step 3. Data Filtering:** Filter rows and select columns that do not contain information for modeling or that do not match the scope of the business;
- **Step 4. Exploratory Data Analysis:** Explore the data to find insights and better understand the impact of variables on model learning;
- **Step 5. Data Preparation:** Prepare the data so that the Machine Learning models can learn the specific behavior;
- **Step 6. Feature Selection:** Selection of the most significant attributes for training the model;
- **Step 7. Machine Learning Modelling:** Machine Learning model training;
- **Step 8. Hyperparameter Fine Tunning:** Choose the best values for each of the parameters of the model selected from the previous step;
- **Step 9. Convert Model Performance to Business Values:** Convert the performance of the Machine Learning model into a business result;
- **Step 10. Deploy Modelo to Production:** Publish the model in a cloud environment so that other people or services can use the results to improve the business decision.

# 4. Top 3 Data Insights

# 5. Machine Learning Modelo Performance

# 6. Business Results

# 7. Conclusions

# 8. Lessons Learned

# 9. Next Steps to Improve
