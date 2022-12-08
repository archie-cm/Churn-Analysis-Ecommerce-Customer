## Full Stack Data - Churn Analysis Ecommerce Customer

**Problem Statement :**
The E-commerce customer churn rate is up to 80% compared with traditional business customer management (Wu & Meng, 2016). From dataset customer churn is 17%.

**Goals :**
The purpose of this project is to predict customer churn, loss opportunity and provide recommendations to the business team so the company can implement a persona customer retention strategy and can monitoring throught dashboard interactive.

**Result :**
The results show that tenure and complaint has the greatest impact on a churn rate. With applying an actionable recommendation from insights, company can avoid loss oppurtunity up to $900,000 and revenue lift up to $ 150,000.

**Tools**: Python, JupyterLab, Git, PowerBI

**Libraries**: Pandas, Numpy, Feature-engine, Scikit-learn, Imbalanced-learn, kaplan-meier survival curve, lifelines.CoPHfilter, lifelines.predict_survival_function, K-means, gaussian, rfm-segmentation

**Dataset**: Ecommerce Customer Churn Analysis and Prediction [[source]](https://www.kaggle.com/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction)

**Summary of the analysis**
* This dataset has 5630 observations and 20 variables with 15 numerical variables, 5 categorical variables and 2 target variable.
* From the data visualization, it is obtained that the churn ratio has a correlation with tenure, complaints, cashback Amount, & preferred order cat.
* The results of predicting churn are strongly influenced by the level of Tenure, Complaint, Number of Addresses, and cashback Amount.
* The results of the Survival Analysis, the customer has the greatest survival chance in No Complain, Marital Status Married, Payment Mode Credit Card, Order Category Grocery.
* RFM Segmentation results show priority customer treatment in the Loyal, New, Promising, and Lost Potential segments. 
* Total Expected Loss of $ 910,687
* Estimated Revenue Uplift
  *  Order category Grocery $42,448
  *  Payment Credit Card $ 91,785 
  *  Payment Debit Card $ 78,543

![image](https://user-images.githubusercontent.com/108534539/206370164-cb8e97d4-f39f-48d1-9a86-2d8e265f25a5.png)


**What I have learned**
* Framing the business problem. 
* Create a machine learning model and extract insight that generates churn & retention from it to make an actionable recommendation for the business team.
* Create a survival analysis, predict customer who will churn in Future and extract insight that generates churn & retention from it to make an actionable recommendation for the business team.
* Create a customer segmentation with RFM Segmentation, KMeans and Gaussians that can generates strategy-strategy personal customer. 
* Create a dashboard interactive can monitoring business metrics, operational, and sales.
* Make a business simulation from insights that calculate loss oppurtunity and revenue uplift.

**File Dictionaries**
* [EDA_Churn_Analysis_Ecommerce_Customer_.ipynb](https://github.com/archie-cm/Churn-Analysis-Ecommerce-Customer/blob/main/EDA_Churn_Analysis_Ecommerce_Customer_.ipynb): this notebook contains all of project details, such as business understanding, exploratory data analysis & insights from bivariate and multivariate analysis
* [Supervised_Classification_Churn_Analysis_Ecommerce_Customer.ipynb](https://github.com/archie-cm/Churn-Analysis-Ecommerce-Customer/blob/main/Supervised_Classification_Churn_Analysis_Ecommerce_Customer.ipynb): data preprocessing, Selection Models & Cross Validation, Handling Imbalance, 
Hyperparameter Tuning, Feature Importance with SHAP
* [Model_Survival_Analysis_Churn_Analysis_Ecommerse_Customer.ipynb](https://github.com/archie-cm/Churn-Analysis-Ecommerce-Customer/blob/main/Model_Survival_Analysis_Churn_Analysis_Ecommerse_Customer.ipynb): Using Kaplan-Meier (KM) and COx Proportional Hazard (CPH) Model, Business Recommendation, Loss Oppurtunity and Revenue Lift
* [Unsupervised_Churn_Analysis_Ecommerce_Customer.ipynb](https://github.com/archie-cm/Churn-Analysis-Ecommerce-Customer/blob/main/Unsupervised_Churn_Analysis_Ecommerce_Customer.ipynb): Using RFM Segmentation, K-Means, and Gaussian, Business Recommendation and Customer Segmentation & Strategy
* [ANN_E-Commerce.pbix](https://github.com/archie-cm/Churn-Analysis-Ecommerce-Customer/blob/main/ANN_E-Commerce.pbix): dashboard interactive to monitoring business metrics
* [Churn Analysis Ecommerce Customer-Presentasi-ANNTeam_TSDN-2022.pdf](https://github.com/archie-cm/Churn-Analysis-Ecommerce-Customer/blob/main/Churn%20Analysis%20Ecommerce%20Customer-Presentasi-ANNTeam_TSDN-2022.pdf): summary of the project.
