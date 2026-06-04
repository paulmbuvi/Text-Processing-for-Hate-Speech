# 🛡️Text Processing for Hate Speech Detection
A Natural Language Processing (NLP) pipeline for preprocessing and exploratory data analysis (EDA) of hate speech data. This project focuses on cleaning, tokenizing, and visualizing text data in preparation for hate speech classification tasks.

# 📋 Project Overview
This project implements a full text preprocessing pipeline on a hate speech dataset. The goal is to transform raw, noisy social media text into clean, structured data suitable for downstream machine learning models.

# 📂 Repository Structure
Text-Processing-for-Hate-Speech/
│
├── Hate_Speech_Preprocessing_EDA.ipynb   # Main notebook with full pipeline
├── README.md                              # Project documentation

Note: The dataset is hosted on Google Drive due to its size (37.7 MB). It is downloaded automatically when you run the notebook.


# ⚙️ Pipeline Steps

Data Loading — Load dataset directly from Google Drive via gdown
Text Cleaning — Remove URLs, punctuation, numbers, and special characters
Lowercasing — Normalize text to lowercase
Tokenization — Split text into individual tokens using NLTK
Stopword Removal — Filter out common English stopwords
Duplicate Removal — Drop duplicate entries based on processed text
Exploratory Data Analysis (EDA) — Word cloud visualization of cleaned text


# 🚀 How to Run

Open the notebook in Google Colab:
Show Image
Run all cells from top to bottom — the dataset will download automatically.
No manual file uploads needed!


# 🧰 Dependencies
pythonpip install gdown nltk autocorrect wordcloud matplotlib pandas
All required installs are included at the top of the notebook.

# 📊 Dataset
The dataset (OmbuiHSRaw.csv) contains raw text samples labelled for hate speech. It is hosted publicly on Google Drive and downloaded programmatically within the notebook.

# 👤 Author
Paul Mbuvi
Student ID: 669984
Assignment One — Text Processing for Hate Speech
Date: June 4, 2026

# 📄 License
This project is for academic purposes only.
