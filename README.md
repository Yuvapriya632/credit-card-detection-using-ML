# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques.
It helps financial institutions identify suspicious activities and reduce financial losses.

The system is built with:

* 🧠 Machine Learning model for prediction
* 🌐 Django-based frontend for user interaction

---

## 🚀 Features

* Detects fraudulent vs genuine transactions
* User-friendly web interface using Django
* Real-time prediction based on input data
* Scalable and easy to integrate

---

## 🛠️ Tech Stack

* **Frontend:** Django (HTML, CSS)
* **Backend:** Python
* **Machine Learning:** Scikit-learn, Pandas, NumPy
* **Visualization:** Matplotlib / Seaborn

---

## 📂 Project Structure

```
CreditML/
│── Backend/
│   └── Credit.ipynb , data.csv                   
│
│── frontend/
│── Credit/                # Django Project (KEEP THIS)
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
│── base/                  # Django App (RENAME from frontend/base)
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
│
│── templates/             # MOVE OUTSIDE (important )
│   ├── base.html
│   ├── home.html
│   ├── index.html
│   ├── login.html
│   ├── logout.html
│   ├── result.html
│   └── signup.html
│
│── static/                # KEEP SAME
│   ├── css/
│   └── images/
│__  DT.pkl                #model save file 
│── manage.py
│── requirements.txt
│── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/Yuvapriya632/credit-card-detection-using-ML.git
cd credit-card-detection-using-ML
```

### 2️⃣ Create virtual environment

```
python -m venv env
env\Scripts\activate
```

### 3️⃣ Install dependencies

```
pip install -r requirements.txt
```

### 4️⃣ Run the Django server

```
python manage.py runserver
```

### 5️⃣ Open in browser

```
http://127.0.0.1:8000/
```

---

## 🎥 Project Demo

Watch the full explanation here: https://youtu.be/7-E4UEmbLr8?si=L2IqDglhiDJPj7TO

---

## 📊 How It Works

1. User inputs transaction details
2. Data is processed using trained ML model
3. Model predicts whether transaction is **Fraudulent** or **Legitimate**
4. Result is displayed on the web interface

---

## 📈 Future Improvements

* Deploy model on cloud (AWS / Render)
* Add real-time dataset integration
* Improve model accuracy with advanced algorithms
* Add authentication system

---
  
## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

## 👩‍💻 Author

**Yuvapriya S.**
AI & Machine Learning Engineer

---
