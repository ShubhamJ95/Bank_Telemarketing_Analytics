# Bank_Telemarketing_Analytics

# Problem Statement
Task 1:- Prepare a complete data analysis report on the given data.

Task 2:- Create a predictive model which will help the bank marketing team to know which customer will buy the product.

Task3:- Suggestions to the Bank market team to make customers buy the product.

----------------------------------------------------------------------------------------------------------------
# Objective: Increase the effectiveness of the bank's telemarketing campaign
- This project will enable the bank to develop a more granular understanding of its customer base, predict customers' response to its telemarketing campaign and establish a target customer profile for future marketing plans.

- By analyzing customer features, such as demographics and transaction history, the bank will be able to predict customer saving behaviours and identify which type of customers is more likely to make term deposits. The bank can then focus its marketing efforts on those customers. This will not only allow the bank to secure deposits more effectively but also increase customer satisfaction by reducing undesirable advertisements for certain customers.

-----------------------------------------------------------------------------------------------------------------
# Project Summary :
- The main goal of this project was to be able to predict which customers would subscribe to a term deposit for Bank Of Portugal. The project uses data collected by the Bank of Portugal that includes customers profiles of those who have subscribed to term deposits and the ones who did not subscribe to a term deposit.

- We were able to analyse the bank marketing dataset, we built different models which helpus to analyse the dataset properly, we classify the dataset according to the data preparing description. We showed various plots for easy reading and understanding.

- According to previous analysis, a target customer profile can be established. The most responsive customers possess feature like age, job, marital status, education etc.

- After the EDA, the dataset was preprocessed by using converting categorical variables,removing outliers, scaling some numerical columns.

- Performed models are decision tree, random forest, naive bayes, xgboost, logistic regression, knn, support vector classifiers to be compared by the use of precision, recall, f1-score,confusion matrix and based on that the RandomForest classifier came out on top with accuracy of 0.93.

---------------------------------------------------------------------------------------------------------------------
# There are some of challenges that as a team we face are :
1. Poor Quality of Data:
Data plays a significant role in the ML process. One of the significant issues our team face is the absence of good quality data. Unclean and noisy data can make the whole process extremely exhausting. We don’t want our algorithm to make inaccurate or faulty predictions. Hence the quality of data is essential to enhance the output. Therefore, we need to ensure that the process of data preprocessing which includes removing outliers, filtering missing values, and removing unwanted features, is done with perfection.

2. Underfitting of Training Data:
This process occurs when data is unable to establish an accurate relationship between input and output variables.It signifies the data is too simple to establish a precise relationship.
To overcome this issue: Maximize the training time,add more features to the data, increasing the training time of model.

3. Overfitting of Training Data:
Overfitting refers to ML model trained with a massive amount of data that negatively affect its performance.
We can tackle this issue by: Analyzing the data with perfection, remove outliers in the training set, remove unwanted feature like duration.

4. Slow optimisation process:
This is one of the common issues faced at the time of model optimisation. The machine learning models are highly efficient in providing accurate results, but it takes a tremendous amount of time. We optimised two model one is Random Forest and another is XG Boost.Random Forest takes more time than XG Boost.

---------------------------------------------------------------------------------------------------------------------------
