# Toxic Comment Classification Using NLP and ML  

Classifies comments into six different categories, including their neutral cases, using concepts of NLP and ML:  

- Toxic  
- Severe Toxic  
- Threat  
- Obscene  
- Insult  
- Identity Hate  

## Concepts Used  

### 1. Data Collection  
- Dataset sourced from Kaggle: [Jigsaw Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge)  

### 2. Data Pre-Processing  
- Removing `\n` characters  
- Removing alphanumeric characters  
- Removing punctuations  
- Removing non-ASCII characters  

### 3. Exploratory Data Analysis (EDA)  
- Bar charts for each category to identify class imbalance  
- Solution: Creating separate datasets for each category to balance class distribution  

### 4. Model Building  
- **Vectorization:** TF-IDF with Unigram Approach  
- **Models Evaluated:** KNN, Logistic Regression, SVM, CNB, BNB, Decision Tree, Random Forest  
- **Selected Model:** Logistic Regression  
- **Model Export:** Trained ML models and vectorizers saved as `.pkl` files  

### 5. Deployment  
- Built a web application using **Streamlit**  
- Deployment on **Streamlit Cloud**  
