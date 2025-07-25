# 📰 Fake News Detection using Python 🧠

A machine learning project to detect fake news using Python and NLP.  
It helps in identifying whether a news article is **REAL** or **FAKE**, thereby promoting information accuracy.

---

## 📌 Project Objective

Develop a classification model that analyzes the **text of news articles** and predicts whether it is **real or fake**, using **Natural Language Processing (NLP)** and **Machine Learning** techniques.

---

## 🧰 Tech Stack Used

- 🐍 Python (Jupyter Notebook)
- 📊 Pandas & NumPy – Data handling
- 📈 Matplotlib & Seaborn – Data visualization
- 🧹 NLTK – Text preprocessing (stopwords, punctuation, lemmatization)
- 🧠 scikit-learn – TfidfVectorizer, PassiveAggressiveClassifier

---

## 📂 Dataset

- **File**: `news.csv`
- **Columns**:
  - `text` – News content
  - `label` – REAL or FAKE

---

## 📊 Project Steps

### 1. 📥 Data Loading
- Loaded `news.csv` using pandas

### 2. 📊 EDA (Exploratory Data Analysis)
- Count plots of real vs fake news
- Text length distribution
- Null values and duplicates check

### 3. 🧽 Text Preprocessing
- Lowercasing
- Removing stopwords and punctuation
- Tokenization and Lemmatization using `nltk`

### 4. 📐 Feature Extraction
- Converted text to numeric features using `TfidfVectorizer`

### 5. ✂️ Train-Test Split
- Split data into training and testing sets

### 6. 🧠 Model Building
- Trained a `PassiveAggressiveClassifier` from scikit-learn

### 7. 📏 Evaluation
- Accuracy Score
- Confusion Matrix
- Final Prediction

---

## ✅ Results

- **Model Accuracy**: ~94%
- **Performance**: Accurately distinguishes between real and fake news articles

---

## 📈 Output Sample


---

## 🧠 Future Improvements

- Use of advanced NLP models like **BERT** or **RoBERTa**
- Add real-time fake news detection using web scraping
- Deploy the project using **Flask** or **Streamlit**

---

## 📄 License

This project is open-source and free to use.

---

> Made with ❤️ for learning and real-world application in detecting misinformation.

