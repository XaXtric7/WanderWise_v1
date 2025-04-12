# 🌍 WanderWise - Traveler Guide System

A full-stack AI-powered travel companion that helps users explore the world with smart routing, real-time travel predictions, and personalized recommendations — anywhere on Earth! 🌐✨

---

## 📷 Screenshots

![Image](https://github.com/user-attachments/assets/a2c03149-f682-4196-b52a-944da7c60c9a)

![Image](https://github.com/user-attachments/assets/0ff650c1-3b91-476c-a80b-c7048de78d39)

![Image](https://github.com/user-attachments/assets/9abb6e53-53bf-48c6-91b4-597a27306f93)

![Image](https://github.com/user-attachments/assets/6b1d14ee-8a69-4db4-8bb3-6ded3496aeb1)

![Image](https://github.com/user-attachments/assets/83417a85-394c-4731-a456-0adaebfc0e15)

## 🔹 Key Features

- 🗺️ **Interactive Google Maps** with dynamic route visualization
- 🔍 **Location Autocomplete** for selecting source & destination
- 🧠 **AI-Powered Routing** using:
  - Dijkstra's Algorithm
  - A\* (A-Star) Search
  - BFS & DFS (for alternative paths and debugging)
- ⏱️ **Travel Time Prediction** using **Random Forest Regression**
- 🍽️🏨 **Smart Recommendations** for:
  - Nearby **restaurants**, **hotels**, and **gas stations** en route
  - Places around your **destination**
- 💱 **International Travel Support**:
  - Auto-detects destination **country & currency**
  - Shows prices in **local currency**
- ⚙️ **Route Preferences**:
  - No tolls
  - Shortest or safest route
  - Most scenic route
- 💾 Save and reload your favorite routes

---

## 🛠️ Tech Stacks

- **Frontend**: React.js + Chakra UI + Google Maps JavaScript API
- **Backend**: Node.js (Express)
- **ML Models**: Python (scikit-learn, TensorFlow)
- **Database**: MongoDB (local or MongoDB Atlas)

---

## 🚀 Getting Started

### ⚙️ Prerequisites

- Node.js (v14 or later)
- Python (v3.7+)
- MongoDB (installed locally or use MongoDB Atlas)
- Google Maps API Key (with Maps + Places API enabled)

---

### 🔧 Backend Setup

```bash
cd backend
npm install
npm run dev

```

### 🌐 Frontend Setup

```bash
cd frontend
npm install
npm start

```

### 🤖 ML Models Setup

```bash
cd ml_models
pip install -r requirements.txt
python travel_time_prediction.py
python place_recommendation.py

```

Made with ❤️ by Team WanderWise
