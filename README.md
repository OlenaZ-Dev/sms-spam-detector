# 📱 SMS Spam Detection using Logistic Regression (NLP Project)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/OlenaZ-Dev/sms-spam-detector/blob/main/sms_spam_detector.ipynb)

---

## 🇬🇧 English

### 📌 Project Overview
This project is an example of **Natural Language Processing (NLP)** applied to SMS spam detection using **TF-IDF vectorization** and **Logistic Regression**.  
It was created as a portfolio project to demonstrate skills in **data preprocessing, model training, evaluation, and interpretation**.

### 🎯 Goal
Classify SMS messages into two categories:
- **Ham** — regular messages
- **Spam** — unwanted promotional or fraudulent messages

The project uses:
- **TF-IDF Vectorization** for text feature extraction  
- **Logistic Regression** for classification  
- Basic **text cleaning** (removing URLs, numbers, punctuation)

### 📂 Dataset
Public dataset **SMS Spam Collection**:  
[https://raw.githubusercontent.com/justmarkham/pycon-2016-tutorial/master/data/sms.tsv](https://raw.githubusercontent.com/justmarkham/pycon-2016-tutorial/master/data/sms.tsv)  

- **Rows**: 5572 messages  
- **Columns**: `label` (ham/spam), `text` (SMS content)

### 📊 Model Results
- **Accuracy**: 0.98  
- **Precision (Spam)**: 0.98  
- **Recall (Spam)**: 0.83  

Confusion Matrix:  

|               | Predicted Ham | Predicted Spam |
|---------------|--------------|----------------|
| **Actual Ham**  | 901          | 2              |
| **Actual Spam** | 22           | 109            |

---

## 🇵🇱 Polski

### 📌 Opis projektu
Ten projekt to przykład **Przetwarzania Języka Naturalnego (NLP)** do wykrywania spamu SMS przy użyciu **wektoryzacji TF-IDF** i **Regresji Logistycznej**.  
Został stworzony jako projekt portfolio, aby pokazać umiejętności w zakresie **czyszczenia danych, trenowania modelu, ewaluacji i interpretacji wyników**.

### 🎯 Cel
Klasyfikacja wiadomości SMS do dwóch kategorii:
- **Ham** – zwykłe wiadomości
- **Spam** – niechciane wiadomości promocyjne lub oszukańcze

Projekt wykorzystuje:
- **TF-IDF Vectorization** do ekstrakcji cech tekstowych  
- **Regresję Logistyczną** do klasyfikacji  
- Podstawowe **czyszczenie tekstu** (usuwanie URL, liczb, interpunkcji)

### 📊 Wyniki modelu
- **Dokładność (Accuracy)**: 0.98  
- **Precyzja (Spam)**: 0.98  
- **Recall (Spam)**: 0.83  

Macierz pomyłek:  

|                | Ham przewidziany | Spam przewidziany |
|----------------|-----------------|-------------------|
| **Ham rzeczywisty**  | 901             | 2                 |
| **Spam rzeczywisty** | 22              | 109               |

---

## 🛠 Technologies / Technologie 
- Python 3.x  
- Pandas, NumPy  
- Scikit-learn  
- Joblib  
- Matplotlib (EDA)

---

## 🚀 How to Run
```bash
# Clone the repository
git clone https://github.com/OlenaZ-Dev/sms-spam-detector.git
cd sms-spam-detector

# Install dependencies
pip install -r requirements.txt

# Run the notebook or script
