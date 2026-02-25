# 🚗 Vehicle Maintenance Predictor  
### Predictive Maintenance Using Machine Learning

---

## 🌐 Live Demo

🔗 Live Application: https://your-app-name.onrender.com  


---

## 📌 Project Overview

Vehicle Maintenance Predictor is a Machine Learning-based web application that predicts whether a vehicle requires maintenance using sensor data.

The system analyzes vehicle sensor readings and determines if maintenance is required, helping to:

- Reduce unexpected breakdowns  
- Improve vehicle reliability  
- Lower maintenance costs  
- Enhance vehicle safety  

---

## 🎯 Objective

To develop a predictive maintenance system that:

- Uses vehicle sensor data  
- Applies Machine Learning algorithms  
- Detects failures before breakdown  
- Provides predictions through a web interface  

---

## 🛠️ Technologies Used

- Python  
- Flask  
- Scikit-learn  
- Pandas  
- NumPy  
- HTML  
- CSS  
- Gunicorn  
- Render (Deployment)

---

## 📂 Project Structure

```
vehicle-maintenance-predictor/
│
├── app.py                  # Flask web application
├── train.py                # Model training script
├── model.pkl               # Trained ML model
├── scaler.pkl              # Feature scaler
├── vehicle_sensor_data.csv # Dataset
├── requirements.txt        # Dependencies
├── Procfile                # Deployment configuration
└── templates/              # HTML files
```

---

## ⚙️ How It Works

1. User enters vehicle sensor values in the web interface.
2. Input data is scaled using `scaler.pkl`.
3. The trained ML model (`model.pkl`) predicts:
   - Maintenance Required  
   - No Maintenance Required  
4. The result is displayed on the webpage.

---

## 🚀 Installation & Local Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/ragasowmya7780/Vehicle_maintenaince_predictor.git
cd Vehicle_maintenaince_predicto
```

### 2️⃣ Create Virtual Environment (Optional)

```
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 4️⃣ Run the Application

```
python app.py
```

Open in browser:

```
http://127.0.0.1:5000/
```

---

## 🔁 Model Training

To retrain the model:

```
python train.py
```

This will regenerate:

- model.pkl  
- scaler.pkl  

---

## 🌍 Deployment

This project is deployed using **Render**.

Build Command:
```
pip install -r requirements.txt
```

Start Command:
```
gunicorn app:app
```

---

## 📊 Dataset

The dataset contains vehicle sensor readings such as:

- Engine Temperature  
- Oil Pressure  
- Vibration  
- Speed  
- Runtime  

Target:
Maintenance Required (Yes / No)

---

## 📈 Future Improvements

- Real-time IoT integration  
- Dashboard with charts  
- Database integration  
- User authentication  
- Advanced ML models  

---

## 👩‍💻 Author

Sowmya Reddy  
Data Analytics Student  

---

## 📜 License

This project is developed for educational purposes.
