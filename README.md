# 🌱 Smart Crop AI

An AI-powered web application that recommends the best crop and fertilizer based on soil nutrients and environmental conditions.

---

## 🚀 Features

### 🌾 Crop Recommendation

* Predicts the best crop using Machine Learning
* Based on:

  * Nitrogen (N), Phosphorus (P), Potassium (K)
  * Temperature, Humidity
  * pH level & Rainfall

### 🧪 Fertilizer Recommendation

* Suggests suitable fertilizer
* Calculates required quantity:

  * Urea
  * DAP
  * MOP

### 🌦 Weather Integration

* Uses real-time weather API
* Auto-fetches:

  * Temperature
  * Humidity

### 📊 Smart Dashboard

* Interactive charts using Chart.js:

  * NPK levels
  * Environmental conditions

### 🧠 AI Explanation

* Provides reasoning for crop recommendation

### 🔊 Telugu Voice Support

* Speaks crop recommendation in Telugu

### ⚙ Settings Page

* Temperature unit (Celsius/Fahrenheit)
* Fertilizer type (Organic/Chemical)
* Default soil selection
* Season selection

---

## 🛠 Tech Stack

### 🔹 Frontend

* HTML
* CSS (Glass UI)
* JavaScript
* Chart.js

### 🔹 Backend

* Python
* Flask

### 🔹 Machine Learning

* Scikit-learn
* Pandas, NumPy
* Joblib

### 🔹 APIs

* OpenWeatherMap API

---

## 📂 Project Structure

```bash
Crop-Project/
│
├── static/
│   └── style.css
│
├── templates/
│   ├── index.html
│   ├── result.html
│   ├── settings.html
│   ├── login.html
│   └── register.html
│
├── crop_model.pkl
├── fert_model.pkl
├── scaler_crop.pkl
├── scaler_fert.pkl
├── soil_encoder.pkl
├── crop_encoder.pkl
│
├── app.py
└── README.md
```

---

## ⚙ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/smart-crop-ai.git
cd smart-crop-ai
```


### 3️⃣ Install Dependencies

```bash
pip install flask pandas numpy scikit-learn joblib requests
```

### 4️⃣ Run Application

```bash
python app.py
```

👉 Open in browser:

```
http://127.0.0.1:5000
```

---

## 🔑 API Setup

Update your API key inside `app.py`:

```python
API_KEY = "53b45011c72ab8378aed46fbfb63ff9d"
```

---

## 🎯 Future Enhancements

* 📊 Prediction history dashboard
* 🌙 Dark/Light mode
* 🌐 Multi-language support
* ☁ Cloud deployment

---



## 💡 Tagline

> “Smart farming powered by AI for better crop decisions 🌱”
# Smart-corp-AI-Dashboard
