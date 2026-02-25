# ⚙️ Setup Instructions  
Vehicle Maintenance Predictor

This guide explains how to set up and run the project locally.

---

## 📋 Prerequisites

Make sure the following are installed:

- Python 3.9 or above
- pip (Python package manager)
- Git (optional, for cloning repository)

Check Python version:

```
python --version
```

---

## 🚀 Step 1: Clone the Repository

```
git clone https://github.com/ragasowmya7780/Vehicle_maintenaince_predictor.git
cd Vehicle_maintenaince_predictor
```

---

## 🐍 Step 2: Create Virtual Environment (Recommended)

### Windows
```
python -m venv venv
venv\Scripts\activate
```

### Mac/Linux
```
python3 -m venv venv
source venv/bin/activate
```

---

## 📦 Step 3: Install Dependencies

```
pip install -r requirements.txt
```

This will install:

- Flask  
- scikit-learn  
- pandas  
- numpy  
- gunicorn  
- joblib  

---

## ▶️ Step 4: Run the Application

```
python app.py
```

The application will start at:

```
http://127.0.0.1:5000/
```

Open this URL in your browser.

---

## 🔁 Optional: Retrain the Model

If you want to retrain the ML model:

```
python train.py
```

This will regenerate:

- model.pkl  
- scaler.pkl  

---

## 🌍 Deployment (Render)

If deploying on Render:

Build Command:
```
pip install -r requirements.txt
```

Start Command:
```
gunicorn app:app
```

Make sure these files are committed:

- model.pkl
- scaler.pkl
- requirements.txt
- Procfile

---

## ⚠️ Troubleshooting

- If you get "Module Not Found" → reinstall requirements
- If deployment fails → check Render logs
- Ensure model.pkl and scaler.pkl are in the root folder

---

## ✅ Project Running Successfully!
