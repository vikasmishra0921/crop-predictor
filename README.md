🌾 Crop Recommendation System using Machine Learning

📌 Project Description
This is a Machine Learning–powered Crop Recommendation System, deployed as a Flask web application.
It predicts the most suitable crop to cultivate based on soil nutrients (N, P, K), climate factors (temperature, humidity, rainfall), and pH value.

The goal is to help farmers or agricultural planners make data-driven crop decisions — increasing productivity and sustainability.

🔗 Live App: https://crop-predictor-ro1c.onrender.com

💡 How It Works
The user enters basic soil & weather parameters into a simple form.

The backend processes the input using pre-trained ML models (Random Forest).

Inputs are first scaled using MinMaxScaler and StandardScaler, just like during training.

The model outputs the best crop to cultivate under current conditions.

The result is shown instantly on the same page.

✅ Why This Project Is Special
🌿 Real-world utility: Built for actual farming decisions.

⚙️ Trained on real agricultural data.

🧠 End-to-end ML: Data cleaning, preprocessing, model training, saving with Pickle, and frontend integration.

🌐 Fully deployed: Users can test it live online. No installations needed.

🔍 Example Use Case
You’re a farmer in Maharashtra. You measure your soil’s NPK, see the local weather conditions, and enter them in the form.
The app instantly tells you:
🥬 “Grow Blackgram here — best suited for your land!”
