📰 Fake News Prediction using Machine Learning
📌 Project Overview

Fake news has become a major challenge in the digital era, spreading misinformation rapidly across social media and online platforms.
This project focuses on detecting fake news articles using Natural Language Processing (NLP) and Machine Learning techniques.

The model analyzes the textual content of news articles and predicts whether the news is Real or Fake.

🎯 Objectives

To build an automated system for identifying fake news

To apply NLP techniques for text preprocessing

To train and evaluate machine learning models for classification

To achieve high accuracy in distinguishing real and fake news

🛠️ Technologies & Tools Used

Programming Language: Python

Environment: Jupyter Notebook

Libraries:

Pandas

NumPy

Scikit-learn

NLTK / Regex

Matplotlib / Seaborn

📂 Dataset Description

The dataset consists of two CSV files:

fake.csv – Contains fake news articles

true.csv – Contains real news articles

Each record includes:

Title of the news

News text/content

Subject

Date

The datasets are merged and labeled:

0 → Fake News

1 → Real News

🔍 Data Preprocessing

The following preprocessing steps were performed:

Lowercasing text

Removing punctuation and special characters

Removing stopwords

Text normalization

Feature extraction using TF-IDF Vectorization

🤖 Machine Learning Models Used

Logistic Regression

Random Forest Classifier

These models were trained on the processed dataset and evaluated using:

Accuracy Score

Precision

Recall

F1-Score

Classification Report

📊 Model Performance

The trained models achieved high accuracy in classifying news articles as fake or real.

Evaluation metrics include:

Confusion Matrix

Classification Report

Accuracy Comparison between models

(Exact accuracy values can be found in the notebook output)

▶️ How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/Prakshityadav/Fake-News-Prediction.git
2️⃣ Navigate to the Project Directory
cd Fake-News-Prediction
3️⃣ Install Required Libraries
pip install pandas numpy scikit-learn matplotlib seaborn nltk
4️⃣ Run the Jupyter Notebook
jupyter notebook

Open the notebook file and run all cells sequentially.

🧪 Sample Prediction

The system allows testing with custom news text to predict:

Real News

Fake News

This demonstrates the practical applicability of the model.

📌 Project Structure
Fake-News-Prediction/
│
├── Fake-News-Detection.ipynb
├── fake.csv
├── true.csv
├── README.md
🚀 Future Enhancements

Use advanced models like LSTM / BERT

Deploy as a Web Application (Flask / Django)

Add real-time news scraping

Improve accuracy with hyperparameter tuning

👨‍💻 Author

Prakshit Yadav
B.Tech Computer Science Engineering Student
Passionate about Machine Learning, Data Science, and Software Development

⭐ Acknowledgements

Scikit-learn Documentation

Kaggle Datasets

NLP research resources

📢 Note

This project is built for educational and learning purposes and demonstrates the application of Machine Learning in real-world problems.
