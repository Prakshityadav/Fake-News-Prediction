# 📰 Fake News Prediction using Machine Learning

## 📌 Project Overview
Fake news has become a major challenge in the digital era, spreading misinformation rapidly across social media and online platforms.

This project aims to **detect fake news articles** using **Natural Language Processing (NLP)** and **Machine Learning techniques**.  
The trained model analyzes the **textual content of news articles** and predicts whether the news is **Real** or **Fake**.

---

## 🎯 Objectives
- Build an automated system for identifying fake news  
- Apply NLP techniques for effective text preprocessing  
- Train and evaluate machine learning models for classification  
- Achieve high accuracy in distinguishing real and fake news  

---

## 🛠️ Technologies & Tools Used
- **Programming Language:** Python  
- **Environment:** Jupyter Notebook  

### Libraries
- Pandas  
- NumPy  
- Scikit-learn  
- NLTK / Regex  
- Matplotlib  
- Seaborn  

---

## 📂 Dataset Description
The dataset consists of two CSV files:

- **fake.csv** – Contains fake news articles  
- **true.csv** – Contains real news articles  

Each record includes:
- Title of the news  
- News text/content  
- Subject  
- Date  

### Label Encoding
- `0` → Fake News  
- `1` → Real News  

---

## 🔍 Data Preprocessing
The following preprocessing steps were performed:

- Converting text to lowercase  
- Removing punctuation and special characters  
- Removing stopwords  
- Text normalization  
- Feature extraction using **TF-IDF Vectorization**  

---

## 🤖 Machine Learning Models Used
- **Logistic Regression**  
- **Random Forest Classifier**  

### Evaluation Metrics
- Accuracy Score  
- Precision  
- Recall  
- F1-Score  
- Classification Report  

---

## 📊 Model Performance
The trained models achieved **high accuracy** in classifying news articles as fake or real.

Performance was evaluated using:
- Confusion Matrix  
- Classification Report  
- Accuracy comparison between models  

📌 *Exact accuracy values are available in the notebook output.*

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Prakshityadav/Fake-News-Prediction.git
2️⃣ Navigate to the Project Directory
cd Fake-News-Prediction
3️⃣ Install Required Libraries
pip install pandas numpy scikit-learn matplotlib seaborn nltk
4️⃣ Run the Jupyter Notebook
jupyter notebook

Open the notebook file and run all cells sequentially.

##🧪 Sample Prediction

The system allows users to test custom news text and predicts whether the news is:

Real News

Fake News

This demonstrates the real-world applicability of the model.

## 📌 Project Structure
Fake-News-Prediction/
│
├── Fake-News-Detection.ipynb
├── fake.csv
├── true.csv
├── README.md
## 🚀 Future Enhancements

Implement advanced models such as LSTM or BERT

Deploy the model as a Web Application using Flask or Django

Add real-time news scraping

Improve accuracy through hyperparameter tuning

## 👨‍💻 Author

Prakshit Yadav
B.Tech Computer Science Engineering Student
Passionate about Machine Learning, Data Science, and Software Development

## ⭐ Acknowledgements

Scikit-learn Documentation

Kaggle Datasets

NLP research resources

## 📢 Note

This project is developed for educational purposes and demonstrates the application of Machine Learning and NLP techniques to solve real-world problems.


💾 **Save the file and close the editor**

---

### **4️⃣ Commit & Push to GitHub**
Copy-paste these commands:

```bash
git add README.md
git commit -m "Updated professional README for Fake News Prediction project"
git push
