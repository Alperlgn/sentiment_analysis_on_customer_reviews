# 📝 Sentiment Analysis on Customer Reviews

This project aims to **analyze user reviews** and classify them as **positive or negative**. **Machine learning and deep learning models** were utilized to perform sentiment analysis.

**Dataset:** The analysis was conducted using three different datasets:
- **All Beauty**: Reviews of beauty products
- **Digital Music**: Reviews of digital music products
- **Health and Personal Care**: Reviews of personal care and healthcare products

The datasets were combined to create **training and test sets** for model evaluation.

---

## 🔍 Data Preprocessing

### 📌 Cleaning and Transformation
- **Missing values** were identified and handled appropriately.
- **Text data was cleaned**, ensuring consistency in case formatting and removing unnecessary symbols.
- **Sentiment labels** were created by classifying **ratings of 3 and above as "positive" and others as "negative"**.

### 🏗️ Feature Extraction
- **TF-IDF vectorization** was used to convert words into numerical representations.
- **Tokenization and Padding** were applied for LSTM processing.

---

## 🤖 Modeling and Performance Comparison

### 📊 Applied Models
- **Logistic Regression** (Machine Learning)
- **LSTM (Long Short-Term Memory)** (Deep Learning)

### 📈 Performance Evaluation
| Model | Accuracy | Precision | Recall | F1-Score |
|--------|---------|------------|--------|---------|
| Logistic Regression | 90% | 86% | 80% | 83% |
| LSTM | 91% | 87% | 83% | 85% |

- **LSTM outperformed Logistic Regression** by providing **higher accuracy and better classification of negative reviews.**
- **Confusion Matrix** analysis was conducted to identify model errors.

---

## 🛠️ Technologies Used

- **Python (Pandas, NumPy, Scikit-Learn, TensorFlow/Keras)**
- **Data Visualization (Matplotlib, Seaborn, WordCloud)**
- **Text Processing (NLTK, TF-IDF, Tokenization)**
- **Machine Learning & Deep Learning Techniques**

---

## 📊 Visualization
- **Word Cloud** analysis was used to identify the most frequently mentioned words for each category.
- **Success ranking was determined based on category-based sentiment analysis.**

### 🚀 Key Insights
- **LSTM demonstrated the best performance in sentiment classification.**
- **TF-IDF vectorization effectively prepared text for machine learning models.**
- **Customer reviews were analyzed per category, and a success ranking was created.**

---

This project serves as a great reference for those interested in **Natural Language Processing (NLP) and Sentiment Analysis**. Open to feedback and discussions! 🚀

