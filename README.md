Customer Churn Prediction 📊
A Machine Learning project that predicts whether a customer is likely to churn (leave a service) based on customer-related information such as age, gender, monthly spending, subscription length, and support interactions.

📌 Project Overview
Customer churn is an important problem for businesses because retaining existing customers is often more valuable than acquiring new ones. This project uses different Machine Learning classification algorithms to predict customer churn and compares their performance to identify the best-performing model.

The project includes:

Data loading and exploration
Data cleaning and preprocessing
Exploratory Data Analysis (EDA)
Data visualization
Feature scaling
Training multiple Machine Learning models
Model performance comparison
Confusion matrix analysis
Classification report
ROC-AUC curve comparison
Feature importance analysis
Sample churn predictions
📂 Files in This Repository
├── CUSTOMER_CHURN_PREDICTION.ipynb
├── customer_churn_dataset.csv
└── README.md
📊 Dataset
The dataset contains 1,000 customer records and the following features:

Feature	Description
Customer_ID	Unique identifier for each customer
Age	Age of the customer
Gender	Gender of the customer
Monthly_Spending	Customer's monthly spending
Subscription_Length	Length of the customer's subscription
Support_Interactions	Number of interactions with customer support
Churn	Target variable indicating whether the customer churned
The Customer_ID column is removed before model training because it is not useful for predicting churn.

🔧 Technologies & Libraries Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Plotly
Scikit-learn
XGBoost
Jupyter Notebook / Google Colab
🤖 Machine Learning Models
The following classification models are trained and compared:

Logistic Regression
Random Forest Classifier
Gradient Boosting Classifier
XGBoost Classifier
The models are evaluated using:

Accuracy
Precision
Recall
F1-Score
ROC-AUC Score
The model with the highest F1-Score is automatically selected as the best model.

🔄 Project Workflow
Dataset
   ↓
Data Loading
   ↓
Data Exploration
   ↓
Data Visualization
   ↓
Data Preprocessing
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Best Model Selection
   ↓
Confusion Matrix & Classification Report
   ↓
ROC-AUC Comparison
   ↓
Feature Importance
   ↓
Sample Predictions
📈 Exploratory Data Analysis
The project explores:

Feature distributions
Customer churn distribution
Gender-wise churn rates
Churn rate based on subscription length
Correlation between numerical features
Various visualizations are created using Matplotlib and Seaborn to understand patterns in the dataset.

🧹 Data Preprocessing
The following preprocessing steps are performed:

Dataset is loaded using Pandas.
Missing values are checked.
Customer_ID is removed.
Features (X) and target (y) are separated.
Data is split into training and testing sets using an 80:20 ratio.
Stratified splitting is used to maintain the class distribution.
Numerical features are standardized using StandardScaler.
📊 Model Evaluation
Each model is evaluated using multiple performance metrics.

The project compares the models based on:

Accuracy
Precision
Recall
F1-Score
ROC-AUC
The F1-Score is used to determine the best-performing model because it balances precision and recall.

The selected best model is further analyzed using:

Confusion Matrix
Classification Report
ROC-AUC Curve
Feature Importance (for tree-based models)
🎯 Sample Prediction
The project also displays sample predictions containing:

Actual Churn Status
Predicted Churn Status
Churn Probability
Whether the prediction was correct
🚀 How to Run the Project
1. Clone the repository
git clone https://github.com/your-username/customer-churn-prediction.git
2. Open the project
Open the CUSTOMER_CHURN_PREDICTION.ipynb notebook using:

Jupyter Notebook
JupyterLab
Google Colab
VS Code
3. Install required libraries
pip install pandas numpy matplotlib seaborn scikit-learn xgboost plotly
4. Run the notebook
Make sure customer_churn_dataset.csv is available in the same working directory as the notebook, then run the notebook cells sequentially.

💡 Key Learning Outcomes
Through this project, I learned how to:

Perform Exploratory Data Analysis
Prepare data for Machine Learning
Split data into training and testing sets
Apply feature scaling
Train multiple classification algorithms
Compare Machine Learning models
Evaluate classification performance
Analyze confusion matrices and ROC-AUC curves
Identify important features
Make predictions using a trained Machine Learning model
🔮 Future Improvements
Some possible improvements for this project are:

Add more customer features to improve prediction accuracy.
Perform hyperparameter tuning for all models.
Use cross-validation for more reliable evaluation.
Handle class imbalance if present in larger real-world datasets.
Create a user-friendly web application using Streamlit or Flask.
Deploy the trained model for real-time churn prediction.
👨‍💻 Author
RUPIN KAUL

GitHub:rup019

⭐ If you found this project useful, consider giving the repository a star!
