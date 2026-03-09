# 📰 Fake News Detector (Machine Learning + Streamlit)

A Machine Learning powered web application that detects whether a news article is **Real or Fake**.
The app uses **Natural Language Processing (NLP)** and a trained classification model to analyze news text and predict its authenticity.

🚀 **Live Demo:**
https://fake-news-detector-itvefuq9uuulymewdjywox.streamlit.app/

---

# 📌 Project Overview

Fake news has become a major issue in the digital era. This project uses **Machine Learning and NLP techniques** to automatically classify news articles as **Real** or **Fake**.

The model is trained on a labeled dataset of real and fake news articles and deployed using **Streamlit** to create an interactive web interface.

---

# 🎯 Features

* Detects **Fake vs Real news articles**
* Clean and interactive **Streamlit UI**
* Uses **Machine Learning text classification**
* Fast prediction using trained model
* Easy to deploy and run locally
* Open-source and beginner friendly

---

# 🧠 Machine Learning Approach

The model follows these steps:

1. Text preprocessing
2. TF-IDF Vectorization
3. Machine Learning classification
4. Prediction using trained model

The trained model and vectorizer are saved as:

```
model.pkl
vectorizer.pkl
```

---

# 🗂 Project Structure

```
fake-news-detector
│
├── app.py
├── model.pkl
├── vectorizer.pkl
├── requirements.txt
└── README.md
```

---

# 📊 Dataset

This project uses the **Fake and Real News Dataset**.

Dataset Source:
https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

The dataset contains:

* **Fake news articles**
* **Real news articles**
* Text content and labels

---

# ⚙️ Installation

Clone the repository:

```
git clone https://github.com/yourusername/fake-news-detector.git
cd fake-news-detector
```

Install dependencies:

```
pip install -r requirements.txt
```

Run the Streamlit app:

```
streamlit run app.py
```

---

# 🌐 Deployment

This project is deployed using **Streamlit Community Cloud**.

Steps to deploy:

1. Push project to GitHub
2. Login to Streamlit Cloud
3. Connect GitHub repository
4. Deploy `app.py`

---

# 🛠 Tech Stack

* Python
* Streamlit
* Scikit-learn
* Pandas
* NLP (TF-IDF)

---

# 📷 Demo

Paste a news article in the text box and click **Predict** to check if it is Fake or Real.

---

# 👨‍💻 Author

Md Faijan Khan

---

# ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
