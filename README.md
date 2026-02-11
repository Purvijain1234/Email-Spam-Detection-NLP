# 📧 Email Spam Detection using NLP

This project is an email spam detection system built using Natural Language Processing (NLP) and machine learning. It classifies emails as **Spam** or **Not Spam (Ham)** using TF-IDF feature extraction and a Multinomial Naive Bayes model. The trained model is deployed using a Streamlit web interface.

---
## 🔄 Workflow

1. Import the email spam dataset  
2. Clean and preprocess the text data  
3. Convert text into numerical features using TF-IDF  
4. Train a Multinomial Naive Bayes machine learning model  
5. Test and evaluate the model  
6. Save the trained model and vectorizer using Pickle  
7. Use the saved model in a Streamlit web application  

---

## 📷 Web Interface Screenshot

<p align="center">
  <img src="https://github.com/user-attachments/assets/d51a9b16-693d-428a-9fe2-f678ec4e07c2" width="48%" />
  <img src="https://github.com/user-attachments/assets/742d4213-85da-4ff2-9a97-e4845dd4630f" width="48%"  />
</p>


The system predicts whether an email message is:

- 🚨 Spam
- ✅ Not Spam

---

## ▶️ How to Run the Project

```bash
1️⃣ Clone the Repository
git clone https://github.com/Purvijain1234/Email-Spam-Detection-NLP.git
cd Email-Spam-Detection-NLP

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Streamlit App
streamlit run app.py
```
---

## 🧹 Text Preprocessing

The following preprocessing steps are applied to the email text:

- Removal of special characters  
- Conversion to lowercase  
- Tokenization  
- Stopword removal  
- Stemming using Porter Stemmer  

---

## 🧠 Machine Learning Model

- **Feature Extraction:** TF-IDF Vectorizer  
- **Model Used:** Multinomial Naive Bayes  
- **Labels:**
  - `1` → Spam  
  - `0` → Not Spam (Ham)

---

## 🛠️ Technologies Used

- Python  
- Pandas    
- NLTK  
- Scikit-learn  
- Streamlit  
- Pickle  

---

## 📄 License

This project is open-source and available under the MIT License.

---
