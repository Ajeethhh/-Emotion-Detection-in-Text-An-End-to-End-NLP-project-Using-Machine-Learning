# -Emotion-Detection-in-Text-An-End-to-End-NLP-project-Using-Machine-Learning
## Project Overview
This project implements an end-to-end Natural Language Processing (NLP) pipeline to detect emotions in text. By leveraging machine learning models like Logistic Regression and Naïve Bayes, the system classifies text into categories such as joy, sadness, anger, fear, and more. The pipeline is designed for robustness, efficiency, and future deployment.

## Dataset
The dataset contains text samples labeled with corresponding emotions. Data exploration and visualization were performed to understand the distribution of emotions and prepare the data for modeling.

## Methodology

### Data Exploration & Visualization
- Analyzed the distribution of emotions using pandas and visualized with seaborn.
- Gained insights into class balance and text characteristics.

### Data Cleaning
- Cleaned text using the `neattext` library by removing user handles, stopwords, and irrelevant characters.
- Created a `Clean_Text` column to store the processed text.

### Feature Engineering
- Defined features (cleaned text) and labels (emotions).
- Split data into training and test sets using `train_test_split` from scikit-learn.

### Model Building
- Built an ML pipeline using scikit-learn’s `Pipeline`.
- Integrated `CountVectorizer` for text vectorization.
- Trained Logistic Regression and Naïve Bayes classifiers on the training set.

### Model Evaluation
- Evaluated model performance using accuracy score and classification report.
- Assessed predictions and probabilities for individual text samples.

### Model Saving
- Saved the trained pipeline using `joblib` for future use and deployment.

## Key Skills & Tools
- **Natural Language Processing (NLP)** – Text cleaning, tokenization, vectorization  
- **Machine Learning** – Logistic Regression, Naïve Bayes, classification  
- **Python** – pandas, scikit-learn, seaborn, matplotlib  
- **Data Preprocessing & Cleaning** – neattext  
- **Model Pipeline Development** – sklearn Pipeline  
- **Model Evaluation** – Accuracy, classification report  
- **Deployment Prep** – joblib for saving models  

## Business Impact
- Enables automated detection of emotions in text for applications in customer feedback analysis, social media monitoring, and sentiment tracking.  
- Supports data-driven decision-making by providing insights into emotional trends in textual data.
