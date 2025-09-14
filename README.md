# 📩 SMS/Email Spam Classifier  

A Machine Learning web application built with **Streamlit** to classify SMS or Email messages as **Spam** or **Not Spam**.  
The project uses **Natural Language Processing (NLP)** techniques and a trained **Machine Learning model** to detect spam messages.

---

## 🚀 Features
- Preprocessing of text (tokenization, stopwords removal, stemming)  
- TF-IDF vectorization for feature extraction  
- Trained ML model (e.g., Naive Bayes / Logistic Regression) for classification  
- Simple and interactive **Streamlit UI**  

---

## 📂 Project Structure

├── app.py # Streamlit application
├── spam.csv # Dataset used for training
├── model.pkl # Trained ML model
├── vectorizer.pkl # Fitted TF-IDF vectorizer
├── nltk.txt # NLTK resources required
└── README.md # Project documentation


## 📊 Dataset
The dataset used is spam.csv containing labeled SMS messages with two classes:

- spam
- ham (not spam)

## 🛠️ Technologies Used

- Python
- Streamlit
- scikit-learn
- NLTK (Natural Language Toolkit)
- Pandas, NumPy

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.
