<p align="center"><b>Artificial Intelligence Major Assignment</b></p>
<br><b>I. Task Background</b></br>
The World Internet Development Report 2022 released during the Wuzhen Summit of the World Internet Conference 2022 showed that in the first quarter of 2022, the number of global 5G users increased by 70 million, reaching about 620 million, and the 5G population coverage rate exceeded 25%. According to the forecasts of Ericsson and the Global System for Mobile Communications Association (GSMA), the number of global 5G users will exceed 1 billion by the end of 2022. For telecommunications operators, facing such a huge 5G market, it is also very helpful to conduct user profiling based on some user-side information and further conduct precise marketing for potential 5G users.
<br><b>II. Task Objective</b><br>
The objective of this task is to predict whether each sample in the test set belongs to a 5G user, based on user's basic information and relevant communication data, such as user's phone bill information, data usage, active behavior, subscription plan type, regional information, and other characteristic fields. This prediction will be achieved by training a model using the training data.
<br><b>III. Evaluation Metrics</b></br>
The evaluation metric adopted for this task is AUC (Area Under the Curve), with a higher score indicating better performance.
<br><b>IV. Model Selection</b></br>
In addressing the problem of predicting whether a user is a 5G user, model selection is a crucial step. Based on the task background and objectives, we have chosen five models for modeling and analysis. These five models are Logistic Regression, Decision Tree, Random Forest, Gradient Boosting Tree, and Extreme Gradient Boosting (XGBoost). Among them, Extreme Gradient Boosting performed the best, achieving the highest AUC score.
