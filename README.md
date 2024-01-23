**Flight Price Prediction using Machine Learning**
This project focuses on predicting airline ticket prices using machine learning models. The dataset includes features such as airline, flight details, departure and arrival times, stops, and class. Various regression models, including Linear Regression, Support Vector Machine (SVM), Decision Tree, Random Forest, and XGBoost, were implemented and evaluated.

Dataset Overview
The dataset consists of training and test data, containing information on 20,000 flights. Key attributes include duration, days left until departure, and the target variable - ticket prices.

Data Preprocessing
Data analysis and preprocessing involved handling missing values, scaling numerical features, and encoding categorical variables using techniques like one-hot encoding.

Regression Models
Several regression models were trained and evaluated:

Linear Regression
Support Vector Machine (SVM)
Decision Tree Regression
Random Forest Regression
XGBoost Regression
Model Evaluation
The models were assessed based on metrics like Mean Absolute Error, Mean Squared Error, Root Mean Squared Error, and R-squared Score. Notably, the Decision Tree and Random Forest models showed exceptional performance.

XGBoost Model
XGBoost emerged as the top-performing model, demonstrating high accuracy and outperforming other models. It showcased robustness in handling the dataset, delivering accurate predictions with a high R-squared score.

Prediction and Submission
The final XGBoost model was used to predict ticket prices on the test dataset. The results were formatted and submitted, achieving competitive performance on the Kaggle platform.

Conclusion
The project successfully leverages machine learning techniques to predict airline ticket prices, with XGBoost standing out as the optimal model for this dataset. The findings contribute to the understanding of pricing patterns in the aviation industry.

For detailed code and analysis, refer to the Jupyter notebook in this repository.
