# Mental-Health-Tech-Prediction

### Dataset and task

The dataset used is OSMI Mental Health in Tech, available on Kaggle and collected by the Open Sourcing Mental Health corporation, which measures the attitude and frequency towards mental health disorders in the context of tech workplace. This survey was filled by respondents who suffer from mental health disorders in tech companies to see if any factors can affect the employee to get treatment or not.

The task consists in analyzing the data and predicting individual’s mental health seek of treatment based on different features (e.g. age, gender, country and several answers about workers' mental health related with work) through the deployment of Machine Learning models.

### Pipeline steps:

#### 1) Data pre-processing
- removal of empty, meaningless values and data cleaning

#### 2) Exploratory Data Analysis (EDA)
- analysis of the attributes and their correlation
- considerations about features correlation, specifically within individuals' treatment

#### 3) Data encoding
- encoding of data for model processing 

#### 4) Definition and deployment of different ML models
- Models used for prediction and tuned with hyperparameters:
  - **Support Vector Machine**
  - **Logistic Regressor**
  - **K-Nearest Neighbors**
  - **Random Forest**
  - **XGB Classifier**

#### 5) Models evaluation and conclusions
- comparison of the results obtained by the models with the best found parameters in terms of:
  - accuracy
  - F1-score
  - ROC-AUC score
        
### Libraries

The python notebook uses the following libraries:
- numpy
- pandas
- matplotlib
- seaborn
- sklearn

The *.ipynb* notebook was executed on the [Google Colab](https://colab.research.google.com) platform.
