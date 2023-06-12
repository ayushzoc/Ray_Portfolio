# Ray_Portfolio
Research and Projects

## [Hate Speech Detection: Overview](https://github.com/ayushzoc/hatespeechbert)
* Created a tool that predicts whether a given statement is a hate speech (with test acc. of ~71%) to classify tweets.
* Dataset contains over 110K tweets from various sources.
* Data preprocessing includes deletion of unused features while labels from different sources were appropriately changed.
* Built a classifier to fine tune a BERT model usign PyTorch.
* Compared wiht a base model of just all labeled non-hateful.
* Project was carried out to learn the deeper aspects of transformers and LLMs.
![HEATMAP!](/images/heatmap.png)
![STATE!](/images/State and sector.png)


## [Data Science Salary Estimator: Overview](https://github.com/ayushzoc/job_salary_proj)
* Created a tool that estimates data science salaries (with MAE ~ 11K) to help data science enthusiasts negotiate their income while job search.
* Scraped over 1000 job descriptions from glassdoor using python and selenium.
* Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark.
* Optimized Linear, Lasso and Random Forest Regressors using GridSearchCV to get the best model.
* A simple client facing API using Flask.

## Rossman Stores Sales Prediction using XGBoost (BI Perspective)(https://github.com/ayushzoc/rossmanstoresales)
* Created a model that predicts the sales of the rossman stores (with mean average precision of 0.13 ~ kaggle score) located in thousands of different places.
* Data was obtained from kaggle competition of the Rossman Store Sales with an objective to dive deep into the theoretical and practical concepts of XGBoost.
* Engineered features from the dates given to quantify the age of the store and the time since the competition of the store is open.
* Hyperparamter Tuning of XGBoost was performed to get the best parameters possible.
