#  Predicting Hotel Booking Cancellations with Machine Learning  

##  Overview  
This project applies **machine learning models** to predict hotel booking cancellations, helping hotels optimize occupancy and reduce overbooking risks.  

##  Key Objectives:
- Compare **Logistic Regression, LDA, QDA, Ridge, and Lasso Regression**.
- Adjust classification **thresholds to minimize false positives** (overbooking risk).
- Use **Lasso Regression for feature selection** and assess its impact on model performance.

## Methods Used:
 **Data Cleaning & Preprocessing**  
 **Feature Engineering & Encoding**  
 **Machine Learning Models** (Logistic Regression, LDA, QDA, Ridge, Lasso)  
 **Model Evaluation (Accuracy, MSE, Confusion Matrices, ROC Curve)**  
 **Business Impact Analysis: Overbooking Risk Reduction**  

##  Results Summary:
- **Logistic Regression achieved 79.68% accuracy**, outperforming other models.
- **Lasso Regression reduced features to 27 key predictors** without major accuracy loss.
- **Threshold tuning helped optimize predictions, reducing overbooking risks**.

##  Repository Structure:
📁 hotel-cancellation-prediction/ │── 📄 README.md # Project overview, methodology, key insights
│── 📄 hotel_cancellation_analysis.ipynb # Jupyter Notebook with full analysis
│── 📄 hotel_bookings.csv # Dataset (if not too large)
│── 📄 images/ # Folder containing plots & visualizations


##  Next Steps:
- Try **ensemble models (Random Forest, XGBoost)** for potential improvements.
-  Deploy the best model using **Flask or Streamlit** for real-world hotel applications.
-  Optimize features by testing additional engineered variables.  

 **Author:** *Ayoola Ososanya*  
 **Skills Demonstrated:** Machine Learning, Data Analysis, Feature Engineering, Model Optimization  

