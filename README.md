# 🌍 WanderWise - Traveler Guide System

A full-stack AI-powered travel companion that helps users explore the world with smart routing, real-time travel predictions, and personalized recommendations — anywhere on Earth! 🌐✨

---

## 📷 Screenshots

![Image](https://github.com/user-attachments/assets/29c0d25b-3dfc-4c6e-9a36-07e6bf93c76d)

![Image](https://github.com/user-attachments/assets/ffcde066-eb22-409a-8a84-9529d15b8997)

![Image](https://github.com/user-attachments/assets/e328f435-2dd5-4d3a-9d37-c8846eddd5ce)

![Image](https://github.com/user-attachments/assets/5cf20e9f-6423-4a35-a6fb-7a2ddf378439)

![Image](https://github.com/user-attachments/assets/b656f7b5-73f0-4d0e-bb8b-33ec31e0ec50)

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
