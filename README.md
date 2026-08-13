# DEARNN – Hybrid Deep Learning Approach for Cyberbullying Detection

## Project Overview

DEARNN is a hybrid deep learning approach for detecting cyberbullying in social media text. The proposed method combines the **Dolphin Echolocation Algorithm (DEA)** with an **Elman Recurrent Neural Network (RNN)** to improve cyberbullying detection performance.

The system analyzes social media text and classifies it into different categories of cyberbullying.

## DEARNN Approach

**DEARNN = Dolphin Echolocation Algorithm (DEA) + Elman Recurrent Neural Network (RNN)**

The Dolphin Echolocation Algorithm is used as an optimization approach, while the Elman RNN is used for learning patterns from the text data.

The project also evaluates other machine learning algorithms for comparison.

## Cyberbullying Categories

The system classifies text into the following categories:

* Not Cyberbullying
* Gender
* Religion
* Other Cyberbullying
* Age
* Ethnicity

## Machine Learning Models

The project includes comparison with several machine learning approaches:

* Multinomial Naive Bayes
* Support Vector Machine (SVM)
* Logistic Regression
* Decision Tree Classifier
* SGD Classifier
* Voting Classifier
* Elman RNN
* DEA-RNN (proposed hybrid approach)

## Technologies Used

* Python
* Django
* HTML/CSS
* JavaScript
* MySQL
* Pandas
* Scikit-learn
* NLTK
* WordCloud

## Dataset

The project uses a labeled social media tweet dataset containing different categories of cyberbullying.

The dataset is processed and transformed into features for training and evaluating the classification models.

## System Workflow

1. Social media text is provided as input.
2. The text is preprocessed and cleaned.
3. Text features are extracted.
4. Machine learning and deep learning models are trained.
5. The DEA algorithm is used as part of the proposed optimization approach.
6. The Elman RNN learns patterns from the processed data.
7. The proposed DEA-RNN model classifies the text.
8. The results are displayed through the Django web application.

## Web Application Features

* User registration and login
* User profile
* Cyberbullying detection
* Prediction results
* Cyberbullying category analysis
* Trending topics
* Model performance comparison
* Graphical visualization
* Predicted dataset download
* Service provider/admin dashboard

## Project Structure

```text
dearnn/
├── dearnn/
├── Remote_User/
├── Service_Provider/
├── Template/
├── Datasets.csv
├── Results.csv
├── manage.py
├── .gitignore
└── README.md
```

## Project Objective

The primary objective of DEARNN is to develop an intelligent system capable of identifying cyberbullying content in social media text and classifying the detected content into relevant categories using a hybrid optimization and deep learning approach.

## Note

Sensitive configuration files and credentials are excluded from the repository using `.gitignore`.
