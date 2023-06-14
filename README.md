# Ray_Portfolio
Research and Projects

## Hate Speech Detection: Overview
* Created a tool that predicts whether a given statement is a hate speech (with test acc. of ~71%) to classify tweets.
* Dataset contains over 110K tweets from various sources.
* Data preprocessing includes deletion of unused features while labels from different sources were appropriately changed.
* Built a classifier to fine tune a BERT model usign PyTorch.
* Compared wiht a base model of just all labeled non-hateful.
* Project was carried out to learn the deeper aspects of transformers and LLMs.  

![Python](https://img.shields.io/badge/Python-100000?style=flat&logo=Python&logoColor=5A27B3&labelColor=FFFFFF&color=FFFFFF) ![PyTorch](https://img.shields.io/badge/PyTorch-100000?style=flat&logo=pytorch&logoColor=FF5500&labelColor=FFFFFF&color=FFFFFF) ![HuggingFace](https://img.shields.io/badge/HuggingFace_Transformers-white?logo=HuggingFace) ![Twitter](https://img.shields.io/badge/Twitter-100000?style=flat&logo=Twitter&logoColor=0084FF&labelColor=FFFFFF&color=FFFFFF) <a href='https://github.com/shivamkapasia0' target="_blank"><img alt='Google colab' src='https://img.shields.io/badge/Colab-100000?style=flat&logo=Google colab&logoColor=E75D00&labelColor=FFFFFF&color=FFFFFF'/></a>

[View Code](https://github.com/ayushzoc/hatespeechbert)


## Data Science Salary Estimator: Overview
* Created a tool that estimates data science salaries (with MAE ~ 11K) to help data science enthusiasts negotiate their income while job search.
* Scraped over 1000 job descriptions from glassdoor using python and selenium.
* Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark.
* Optimized Linear, Lasso and Random Forest Regressors using GridSearchCV to get the best model.
* A simple client facing API using Flask.  

![Python](https://img.shields.io/badge/Python-100000?style=flat&logo=Python&logoColor=5A27B3&labelColor=FFFFFF&color=FFFFFF) ![Selenium](https://img.shields.io/badge/Selenium-100000?style=flat&logo=Selenium&logoColor=06A000&labelColor=FFFFFF&color=FFFFFF) ![Jupyter](https://img.shields.io/badge/Jupyter-100000?style=flat&logo=Jupyter&logoColor=FD7200&labelColor=FFFFFF&color=FFFFFF) ![GlassDoor](https://img.shields.io/badge/GlassDoor-100000?style=flat&logo=Glassdoor&logoColor=02C319&labelColor=FFFFFF&color=FFFFFF)  

![STATE!](/images/image1.png)  

[View Code](https://github.com/ayushzoc/job_salary_proj)

## Rossman Stores Sales Prediction using XGBoost (BI Perspective)
* Created a model that predicts the sales of the rossman stores (with mean average precision of 0.13 ~ kaggle score) located in thousands of different places.
* Data was obtained from kaggle competition of the Rossman Store Sales with an objective to dive deep into the theoretical and practical concepts of XGBoost.
* Engineered features from the dates given to quantify the age of the store and the time since the competition of the store is open.
* Hyperparamter Tuning of XGBoost was performed to get the best parameters possible.  

![Python](https://img.shields.io/badge/Python-100000?style=flat&logo=Python&logoColor=5A27B3&labelColor=FFFFFF&color=FFFFFF) ![Kaggle](https://img.shields.io/badge/Kaggle-100000?style=flat&logo=Kaggle&logoColor=00B3FF&labelColor=FFFFFF&color=FFFFFF) ![Jupyter](https://img.shields.io/badge/Jupyter-100000?style=flat&logo=Jupyter&logoColor=FD7200&labelColor=FFFFFF&color=FFFFFF) ![XGBoost](https://img.shields.io/badge/Gradient_Boost-white?logo=GradientBoost)

![State!](/images/image2.png)

[View Code](https://github.com/ayushzoc/rossmanstoresales)

## Drowsiness Detection System using TensorFlow and OpenCV (Computer Vision, Transfer Learning)
* A Computer Vision tool to detect drowsiness in drivers. 
* The system is alerted if the driver is found sleepy/drowsy. 
* The driver is determined sleepy/drowsy if their eyes remain shut for a small threshold amount of time which triggers an alarm to wake the driver up.
* Initially used IMutils for facial detection which resulted in incorrect facial landmark detection multiple times.
* Haarcascades facial landmark detection was used.
* Transfer Learning used from MobileNet.

![Python](https://img.shields.io/badge/Python-100000?style=flat&logo=Python&logoColor=5A27B3&labelColor=FFFFFF&color=FFFFFF) ![TensorFlow](https://img.shields.io/badge/TensorFlow-100000?style=flat&logo=TensorFlow&logoColor=FF8D00&labelColor=FFFFFF&color=FFFFFF) ![Keras](https://img.shields.io/badge/Keras-100000?style=flat&logo=Keras&logoColor=FF1E00&labelColor=FFFFFF&color=FFFFFF) ![OpenCV](https://img.shields.io/badge/Keras-100000?style=flat&logo=OpenCV&logoColor=44FF00&labelColor=FFFFFF&color=FFFFFF)
