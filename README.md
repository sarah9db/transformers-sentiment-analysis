# transformers-sentiment-analysis
A deep learning-based sentiment analysis model using PyTorch, TensorFlow, and Hugging Face Transformers, fine-tuned on a custom IMDb movie review dataset to classify reviews.

IMDb Sentiment Analysis
This repository contains a sentiment analysis project that scrapes movie reviews from IMDb, preprocesses the data, and fine-tunes a transformer-based model using PyTorch and TensorFlow.

🚀 Project Overview
This project aims to classify IMDb movie reviews as positive or negative using deep learning techniques. The dataset is collected through web scraping and processed to create a labeled dataset for training a transformer-based sentiment analysis model.

🔹 Key Features
Automated Web Scraping: Uses Selenium to extract IMDb movie reviews.

Data Preprocessing: Converts ratings into labeled sentiment categories.

Deep Learning Model: Fine-tunes a Hugging Face transformer model to improve classification accuracy.

Performance Optimization: Achieved an 81% accuracy through feature engineering and hyperparameter tuning.

🛠️ Technologies Used
Python

Selenium (for web scraping)

pandas, NumPy (for data processing)

scikit-learn (for data transformation and evaluation)

PyTorch & TensorFlow (for model training)

Hugging Face Transformers (for NLP-based sentiment classification)

📂 Dataset
The dataset consists of IMDb movie reviews, labeled as positive or negative based on ratings. The scraping process ensures a balanced dataset with 500 samples per category.

📊 Results
After fine-tuning the model, the final accuracy improved from 61% to 81%, enhancing sentiment classification performance.
