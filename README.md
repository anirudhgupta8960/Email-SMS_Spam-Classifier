# 📩 Email-SMS Spam Classifier

📩 Email-SMS Spam Classifier** is a Machine Learning-based application that uses **Natural Language Processing (NLP)** to classify text messages as **Spam** or **Not Spam (Ham)**. The project uses **TF-IDF Vectorization** and **Multinomial Naive Bayes** for text classification and provides an interactive interface using **Streamlit**.

# 🚀 Project Overview

Spam messages are unwanted messages that may contain advertisements, suspicious links, scams, or irrelevant content.

This project provides a simple and interactive solution where users can enter an email or SMS message and instantly check whether it is **Spam** or **Not Spam**.

## ✨ Features

- 📩 Classifies Email/SMS messages as **Spam** or **Not Spam**
- 🤖 Machine Learning-based prediction
- 🧹 Text preprocessing using NLP techniques
- 🔤 Tokenization and stopword removal
- 🌱 Stemming for text normalization
- 📊 TF-IDF Vectorization for feature extraction
- ⚡ Fast and simple predictions
- 🖥️ Interactive web interface using Streamlit
- 📱 Easy to use for testing different messages

## 🧠 Machine Learning Workflow

The project follows these major steps:

**Text Input → Text Preprocessing → TF-IDF Vectorization → Multinomial Naive Bayes → Spam/Not Spam Prediction**

### 🔹 Text Preprocessing

The input message is processed using NLP techniques such as:

- Lowercase conversion
- Removal of punctuation and special characters
- Tokenization
- Stopword removal
- Stemming

### 🔹 Feature Extraction

**TF-IDF (Term Frequency–Inverse Document Frequency)** is used to convert text data into numerical features that can be processed by the Machine Learning model.

### 🔹 Classification Model

The project uses **Multinomial Naive Bayes**, which is well suited for text classification problems such as spam detection.

## 🛠️ Technologies & Libraries

- 🐍 Python
- 🎨 Streamlit
- 🐼 Pandas
- 🔢 NumPy
- 📝 NLTK
- 📊 Scikit-learn
- 📓 Jupyter Notebook

## 📂 Project Structure

```text
Email-SMS_Spam-Classifier/
│
├── 📄 sms.py
├── 📄 README.md
├── 📄 requirements.txt
└── 📁 dataset/

▶️ How to Run the Project

1️⃣ Clone the Repository

git clone https://github.com/anirudhgupta8960/Email-SMS_Spam-Classifier.git

2️⃣ Navigate to the Project Folder

cd Email-SMS_Spam-Classifier

3️⃣ Install Required Libraries

pip install -r requirements.txt

4️⃣ Run the Streamlit Application

streamlit run sms.py

The application will open in your browser.

💡 Example

📩 Input

Congratulations! You have won a free prize. Click here to claim now!

🔴 Prediction

Spam

📩 Another Input

Hey, are you coming to college today?

🟢 Prediction

Not Spam

🎯 Objective

The main objective of this project is to demonstrate how Natural Language Processing and Machine Learning can be used to automatically identify unwanted messages.

🌍 Real-World Applications

This type of spam classification system can be useful for:

📧 Email filtering

📱 SMS spam detection

🔐 Identifying suspicious messages

🛡️ Reducing unwanted communication

🤖 Automated message classification


🔮 Future Improvements

📈 Improve model performance with larger datasets

🧠 Experiment with additional Machine Learning algorithms

🌐 Deploy the application for public use

📊 Add prediction confidence/probability

🔗 Extend support for more types of text messages


👨‍💻 Author

Anirudh Gupta

🎓 B.Tech — Computer Science & Engineering (Data Science)
📍 Lucknow, Uttar Pradesh, India

⭐ Project

If you find this project useful or interesting, consider giving it a ⭐ on GitHub!
