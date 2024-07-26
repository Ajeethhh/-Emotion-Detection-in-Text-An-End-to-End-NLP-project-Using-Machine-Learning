# -Emotion-Detection-in-Text-An-End-to-End-NLP-project-Using-Machine-Learning
Emotion Detection in Text: An End-to-End NLP Pipeline Using Logistic Regression

Objective: The primary goal of this project is to develop a robust and efficient pipeline for detecting emotions in text using Natural Language Processing (NLP) techniques and machine learning. By leveraging logistic regression, naive bayes the project aims to classify text into various emotional categories such as joy, sadness, anger, fear, and others.

Dataset: The project utilizes a dataset containing text samples labeled with corresponding emotions. The dataset is loaded and inspected to understand the distribution of emotions and prepare for subsequent processing.

Methodology:

Data Exploration and Visualization:

Load the dataset using pandas and explore the distribution of emotions using value counts. Visualize the data distribution using seaborn to understand the frequency of each emotion category.

Data Cleaning:

Employ the neattext library to clean the text data by removing user handles, stopwords, and other irrelevant components. Create a new column Clean_Text in the dataframe to store the cleaned text.

Feature Engineering:

Define features (cleaned text) and labels (emotions) for the model. Split the data into training and test sets using train_test_split from sklearn.

Model Building:

Construct a machine learning pipeline using sklearn's Pipeline. Integrate CountVectorizer for text vectorization and LogisticRegression for classification. Train the logistic regression model on the training data.

Model Evaluation:

Evaluate the model’s performance on the test set using accuracy score and classification report. Assess model predictions and prediction probabilities for individual text samples.

Model Saving:

Save the trained model pipeline using joblib for future use and deployment.
