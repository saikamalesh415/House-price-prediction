# 🏠 House Price Prediction App

A Machine Learning powered web application that predicts housing prices in Bengaluru based on location, BHK, bathrooms, and square footage.
🚀 Built with a Flask backend (deployed on Render) and a plain HTML/CSS/JS frontend (deployed on Netlify).<br>
#### [Project Demo Link](https://housepricepredictionbengalure.netlify.app/)
--- 

## 📌 Features
- ✅ Predict house prices using trained ML model
- ✅ Input parameters: Location, Square Feet, BHK, Bathrooms
- ✅ REST API built with Flask
- ✅ Frontend built with HTML, CSS, JavaScript
- ✅ Backend deployed on Render
- ✅ Frontend deployed on Netlify
- ✅ Lightweight, beginner-friendly, no frameworks

---

## 🛠️ Tech Stack

### Frontend

- HTML5, CSS3, JavaScript
- AJAX requests (fetch / $.get / $.post)

### Backend

- Python, Flask, Gunicorn (for production server)
- Machine Learning
- Model trained on Bengaluru house price dataset
- Preprocessed features stored in columns.json
- Trained model stored in .pickle file
  
### Deployment

- Backend → Render
- Frontend → Netlify

---

## 📂 Project Structure

```
BHP/
├── client/                # Frontend (Netlify)
│   ├── index.html         # Main UI
│   ├── app.js             # JS logic for API calls
│   ├── app.css            # Styles
│   └── package.json       # (Optional, not required)
│
├── server/                # Backend (Flask + Render)
│   ├── server.py          # Flask app
│   ├── util.py            # Model loading & prediction functions
│   ├── requirements.txt   # Python dependencies
│   └── artifacts/         # Saved ML model + columns
│       ├── Bengaluru_House_Data.pickle
│       └── columns.json
│
├── model/                 # Not used in deployment, contains Jupyter notebook
│   └── pro.ipynb
│
├── README.md              # Project documentation
└── LICENSE

```

---

## ⚡ How It Works

- User enters house details (location, sqft, BHK, bathrooms) in the frontend.
- Frontend makes an API call to the Flask backend (/predict_home_price).
- Flask backend loads the trained ML model and predicts the price.
- Result is returned to frontend and displayed in the UI.

---

## 🔧 Setup Instructions (Local)

### 1️⃣ Clone the repo

```

git clone https://github.com/saikamalesh415/House-price-prediction.git
cd House-price-prediction

```

### 2️⃣ Backend Setup

```

cd server
pip install -r requirements.txt
python server.py

```

- Backend will run at http://127.0.0.1:5000/

### 3️⃣ Frontend Setup

- Simply open client/index.html in your browser.

---

## 🌐 Live Demo

- Frontend (Netlify): 🔗 House Price Predictor
- Backend (Render API): 🔗 House Price API

---

## 📸 Screenshots

### Input Form

<img width="1182" height="798" alt="image" src="https://github.com/user-attachments/assets/bc71d054-fabe-49c6-b2e0-e90de4748173" />


### Redicted Result

<img width="1003" height="788" alt="image" src="https://github.com/user-attachments/assets/a77caeee-1e27-4f8e-b568-96053704d645" />

---

## 🤝 Contributing

- Contributions are welcome!
- Fork the repo
- Create a new branch (feature-xyz)
- Commit changes
- Push and create a PR

---

## 📜 License

This project is licensed under the MIT License.
