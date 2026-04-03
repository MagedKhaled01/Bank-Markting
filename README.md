# Bank Marketing Classification

This project focuses on predicting whether a client will subscribe to a term deposit based on bank marketing campaign data.


##  Objective

Build a machine learning classification model to identify potential customers who are likely to subscribe to a term deposit.


##  Approach

The project follows a structured machine learning pipeline:

- Data preprocessing and cleaning  
- Encoding categorical variables  
- Feature selection using statistical and model-based methods  
- Model training and evaluation  
- Performance comparison across different models  


##  Models Used

- Gradient Boosting Classifier  
- Random Forest Classifier (Final Model)  

Random Forest was selected as the final model after achieving better performance in both accuracy and recall.


##  Results

- Accuracy: **~84.5%**  
- Balanced Precision and Recall across classes  
- Improved detection of positive class (customers likely to subscribe)  


##  Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

These metrics provide a deeper understanding of model performance beyond accuracy.


##  Feature Selection

Feature selection was performed using:

- SelectFromModel (Random Forest)

The selected features represent the most important predictors influencing customer subscription decisions.


##  Key Insights

- Customer interaction features (e.g., call duration, campaign details) showed strong predictive power  
- Ensemble models outperformed simpler models  
- Feature selection improved both performance and interpretability  


##  Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  


##  Dataset

Dataset available on Kaggle:  
https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset

---

##  Conclusion

This project demonstrates a complete machine learning classification pipeline, from preprocessing to evaluation, with a focus on building reliable and interpretable models.

