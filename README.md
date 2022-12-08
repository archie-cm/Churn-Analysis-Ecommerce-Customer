## Full Stack Data - Churn Analysis Ecommerce Customer

The E-commerce customer churn rate is up to 80% compared with traditional business customer management (Wu & Meng, 2016)
![image](https://user-images.githubusercontent.com/108534539/206361392-1515754a-df32-4095-ab11-4ecc6a643dbf.png)


The purpose of this project is to analyze the purchasing behavior patterns of e-commerce visitors and to increase the conversion rate to purchase. The results show that page values, the number of visited pages, has the greatest impact on a visitor's purchase decision. The conversion rate to purchase increases up to 60% by applying an actionable recommendation from insights that boost the number of visited pages.

**Tools**: Python, JupyterLab, Git

**Libraries**: Pandas, Numpy, Feature-engine, Scikit-learn, Imbalanced-learn, lifelines

**Dataset**: Ecommerce Customer Churn Analysis and Prediction, [[source]](https://www.kaggle.com/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction)

**Summary of the analysis**
* This dataset has 12330 observations and 18 variables with 10 numerical variables, 7 categorical variables and one target variable.
* All numerical variables have a right-skewed distribution and contain a lot of outliers. 
* Revenue is the target variable that labels a visitor's purchase decision either purchase (class True) or not purchase (class False). The current condition is only 15% of total visitors who make a purchase. 
* From exploratory data analysis, visitors with low exit and bounce rates and high page values, tend to make a purchase.
* Based on data characteristics, the selected algorithm to build a classification model is tree-based or ensemble. The classification model with the random forest algorithm is able to correctly predict 62% of visitors who make a purchase.
* The result shows that page values, a number of visited pages, are the biggest impact on visitors' purchase decisions. The conversion rate to purchase increases up to 60% by applying an actionable recommendation from insights that boost page values of visitors.

**What I have learned**
* Framing the business problem. 
* Create a machine learning model and extract insight from it to make an actionable recommendation for the business team.
* Make a business simulation from insights that calculate the increase in the conversion rate.

**File Dictionaries**
* [proof-of-concepts.ipynb](https://github.com/irfan-fadhlurrahman/online-shoppers-purchasing-intention/blob/main/proof-of-concepts.ipynb): this notebook contains all of project details, such as business understanding, exploratory data analysis & insights, data preprocessing and modeling.
* [presentation-appendix.ipynb](https://github.com/irfan-fadhlurrahman/online-shoppers-purchasing-intention/blob/main/presentation-appendix.ipynb): this notebook contains all data visualizations for presentation slides and the details of business simulation, a calculation of increased conversion rate after applying an actionable recommendation.
* [Final Project Presentation Slides.pdf](https://github.com/irfan-fadhlurrahman/online-shoppers-purchasing-intention/blob/main/Final%20Project%20Presentation%20Slides.pdf): summary of the project.
* [requirements.txt](https://github.com/irfan-fadhlurrahman/online-shoppers-purchasing-intention/blob/main/requirements.txt): list of used libraries with its version.

**Folder Dictionaries**
* Stage 0 - Stage 4: the progress of the project per each stage.
* dataset: the original data from Kaggle and the data that has been preprocessed.
