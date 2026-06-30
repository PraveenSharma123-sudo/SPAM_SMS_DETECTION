# 📩 SPAM SMS Detection

A Machine Learning and Natural Language Processing (NLP) project that automatically classifies SMS messages as **Spam** or **Ham (Not Spam)**. The project leverages text preprocessing, feature extraction, and machine learning algorithms to accurately detect unwanted messages and reduce spam-related risks.

---

## 📌 Project Overview

Spam SMS messages are commonly used for phishing, scams, and unsolicited advertisements. This project builds an intelligent text classification model that analyzes SMS content and predicts whether a message is spam or legitimate.

The workflow includes:

* Data preprocessing
* Text cleaning
* Feature extraction
* Model training
* Performance evaluation
* Spam prediction

---

## 🚀 Features

* Detects Spam and Ham SMS messages
* Text preprocessing using NLP techniques
* Removes stop words and punctuation
* Converts text into numerical features using TF-IDF or Bag of Words
* Trains Machine Learning classification models
* Evaluates model performance using standard metrics
* Predicts new SMS messages in real time

---

## 🛠️ Technologies Used

* Python
* Scikit-learn
* Pandas
* NumPy
* NLTK
* Matplotlib
* Jupyter Notebook

---

## 📂 Project Structure

```text
SPAM_SMS_DETECTION/
│
├── dataset/
│   └── spam.csv
│
├── notebooks/
│   └── spam_sms_detection.ipynb
│
├── models/
│   └── trained_model.pkl
│
├── app.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/SPAM_SMS_DETECTION.git
```

Move to the project directory:

```bash
cd SPAM_SMS_DETECTION
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the application:

```bash
python app.py
```

Or open the Jupyter Notebook:

```bash
jupyter notebook
```

Enter any SMS message to check whether it is **Spam** or **Ham**.

---

## 📊 Machine Learning Workflow

1. Load SMS dataset
2. Clean and preprocess text
3. Tokenization
4. Remove stop words
5. Text vectorization (TF-IDF/Bag of Words)
6. Train classification model
7. Evaluate model
8. Predict new SMS messages

---

## 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 📸 Sample Output

```text
Input:
Congratulations! You have won a FREE iPhone. Click here to claim.

Prediction:
Spam
```

```text
Input:
Hey, are we meeting at 6 PM today?

Prediction:
Ham
```

---

## 🎯 Future Improvements

* Deep Learning (LSTM/Bi-LSTM)
* BERT-based spam detection
* Flask/Django web deployment
* Streamlit interactive interface
* Real-time SMS API integration
* Multi-language spam detection

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Praveen Sharma**

Passionate about Machine Learning, Artificial Intelligence, NLP, Full Stack Development, and Cybersecurity.

If you like this project, don't forget to ⭐ the repository!
