# Mental-Health-Tech-Prediction

### Dataset and task

The dataset used is OSMI Mental Health in Tech, available on Kaggle, which measures the attitude and frequency towards mental health disorders in the context of tech workplace. This survey was filled by respondents who suffer from mental health disorders in tech companies to see if any factors can affect the employee to get treatment or not.

The task consists in analyzing the data and predicting individual’s mental health treatment based on different features (e.g. age, gender, country and several answers about workers' mental health and work) through the deployment of machine learning models.

### Steps

#### 1) Data pre-processing
- removal of empty, meaningless values and data cleaning

#### 2) Exploratory Data Analysis
- analysis of the attributes and their correlation
- extrapolation of information about mental treatment given the individual's answers

#### 3) Data encoding
- encoding of data for later model processing 

#### 4) Definition and deployment of different models
- five prediction models (Support Vector Machine, Logistic Regressor, K-Nearest Neighbor, Random Forest, XGB Classifier) tuned with hyperparameters

#### 5) Comparison of the models and conclusions
- comparison of the results obtained by the models, tuned by accuracy and f1-macro
        
### Libraries

The notebook uses the following libraries:
- numpy
- pandas
- matplotlib
- seaborn
- sklearn
