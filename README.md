🌾 Crop Recommendation System using Machine Learning

This is a Flask-based web application that recommends the best crop to cultivate based on soil and environmental conditions using a trained Machine Learning model.

🌐 Live Demo

🔗 https://crop-predictor-ro1c.onrender.com/predict

📊 Tech Stack

Frontend: HTML, Bootstrap

Backend: Flask (Python)

ML Model: RandomForestClassifier (Scikit-learn)

Deployment: Render

Model Serialization: Pickle

📁 Project Structure

crop-recommendation-app/
├── app.py                  # Flask app logic
├── model2.pkl              # Trained ML model
├── minmaxscaler2.pkl       # MinMaxScaler
├── standscaler2.pkl        # StandardScaler
├── requirements.txt        # Python dependencies
├── Procfile                # Render startup instructions
├── README.md               # Project overview
└── templates/
    └── index.html          # Web UI form

🧠 How It Works

User inputs Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, Rainfall.

Flask receives the form data.

Input is transformed using MinMaxScaler and StandardScaler.

Pre-trained model predicts the best crop.

The app displays the result on the same web page.
