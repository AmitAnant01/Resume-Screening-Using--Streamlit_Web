
# Resume Category Prediction App

A machine learning-based web application built using Streamlit that predicts the job category of a resume. Users can upload resumes in PDF, DOCX, or TXT format, and the system extracts the text, processes it, and classifies it into a relevant job domain.

## Features

Upload resumes in PDF, DOCX, or TXT format

Automatic text extraction from uploaded files

Text cleaning and preprocessing using regular expressions

TF-IDF vectorization for feature extraction

Classification using a pre-trained Support Vector Classifier (SVC) model

Interactive user interface built with Streamlit

Displays predicted job category in real time



## Tech Stack

Python

Streamlit

Scikit-learn

TF-IDF Vectorizer

PyPDF2

python-docx

Pickle



## Project Structure

├── app.py              # Main Streamlit application
├── clf.pkl            # Trained classification model
├── tfidf.pkl          # TF-IDF vectorizer
├── encoder.pkl        # Label encoder
├── requirements.txt   # Project dependencies
└── README.md          # Documentation


## How It Works

1. The user uploads a resume file


2. The system extracts text based on file format


3. The text is cleaned and preprocessed


4. TF-IDF converts the text into numerical features


5. The trained SVC model predicts the category


6. The result is displayed in the interface




## Use Cases :

Resume screening automation

HR technology tools

Career guidance applications
