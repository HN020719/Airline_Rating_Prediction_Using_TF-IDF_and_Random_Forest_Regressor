# Airline_Rating_Prediction_Using_TF-IDF_and_Random_Forest_Regressor
This project aimed to predict overall ratings from a Kaggle dataset containing various airline reviews. We utilized an ensemble model combining TF-IDF and a Random Forest Regressor, which outperformed other models. The success of this model was driven by effective feature representation and optimization techniques.

Key steps and findings:

1. **Data Analysis:**
   - The dataset indicated a high prevalence of negative reviews, highlighting areas for airline improvement.
   - Features such as 'Seat Comfort,' 'Cabin Staff Service,' and 'Value for Money' were crucial in predicting overall ratings.

2. **Data Preprocessing:**
   - Applied TF-IDF transformation to textual reviews.
   - Employed one-hot encoding for categorical features.
   - Addressed missing values using imputation methods.

3. **Model Training and Evaluation:**
   - Compared Linear Regression, Random Forest, and XGBoost models.
   - The ensemble model (TF-IDF + Random Forest) achieved the lowest Mean Squared Error (MSE) and superior predictive performance.
   - Hyperparameter tuning, especially optimizing "n_estimators," further improved model performance.

4. **Insights and Literature Review:**
   - Confirmed the significance of service-related features in predicting ratings.
   - Explored existing studies and aligned our findings with industry insights.

In conclusion, our ensemble model provided valuable insights into the airline industry, emphasizing the importance of specific service features in predicting overall ratings.
