# Phishing Website Detector 🛡️

A machine learning-based web application that detects whether a given website URL is legitimate or a phishing site.  

Built using:
- Python
- Logistic Regression (Scikit-learn)
- Streamlit for the web app interface

---  

Dataset Source  
Kaggle: Phishing Website URLs Dataset (https://www.kaggle.com/datasets/taruntiwarihp/phishing-site-urls)  

## 🚀 Features

- Accepts website URL input from users.
- Predicts if the URL is **Legitimate** or **Phishing** using a trained Logistic Regression model.
- Displays prediction confidence score.
- Simple and responsive UI using Streamlit.

---

## 📂 Project Structure
PhishingWebsiteDetector/  
│  
├── app.py # Streamlit web app  
├── trainModel.py # Model training script  
├── phishing_site_urls.csv # Dataset  
├── vectorizer.pkl # Saved TfidfVectorizer  
├── log_model.pkl # Saved Logistic Regression model  
├── requirements.txt # Python dependencies  
└── README.md  


---

## ⚙️ How to Run Locally

1️⃣ Clone the repository:  
```bash
git clone https://github.com/Jeevan200431/PhishingWebsiteDetector.git
cd PhishingWebsiteDetector
```
-Install dependencies:  
```pip install -r requirements.txt  ```
-Traim model  
``` python trainModel.py  ```
-run streamlit app  
```streamlit run app.py ``` 





