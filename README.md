 📦 SmartStock – AI-Powered Inventory Forecasting & Alert System

SmartStock is a full-stack machine learning application that helps businesses optimize inventory management by forecasting future product demand and generating intelligent stock alerts. The system reduces inventory-related losses by predicting stock requirements before shortages or overstock situations occur.

---

## 🚀 Features

- 📈 AI-based demand forecasting using XGBoost
- 📊 Interactive inventory analytics dashboard
- 🔔 Real-time stock alerts and notifications
- 📂 CSV sales data upload and processing
- 📅 30-day demand prediction
- 🎯 SKU-level inventory forecasting
- 📉 Overstock and stockout prevention
- 🌐 RESTful APIs powered by FastAPI
- 📱 Responsive and user-friendly interface

---

## 🏗️ Architecture

### Machine Learning Layer
- Data preprocessing and feature engineering
- Time-series feature generation
- Demand forecasting using XGBoost
- Model evaluation and prediction pipeline

### Backend Layer
- FastAPI-based REST API
- Forecast generation endpoints
- Inventory alert engine
- Data processing services

### Frontend Layer
- React.js & Next.js dashboard
- Forecast visualization charts
- Inventory status monitoring
- Alert management interface

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Next.js
- JavaScript
- Recharts

### Backend
- Python
- FastAPI

### Machine Learning
- XGBoost
- Scikit-learn
- Pandas
- NumPy

### Database
- PostgreSQL

---

## 📂 Project Structure

bash
SmartStock/
│
├── backend/
│   ├── demand_model.py
│   ├── feature_engineering.py
│   ├── alert_engine.py
│   └── forecast_routes.py
│
├── frontend/
│   ├── Dashboard.js
│   ├── components/
│   └── pages/
│
├── dataset/
│   └── retail.csv
│
├── models/
│   └── best_model.pkl
│
└── README.md


---

## ⚙️ Installation & Setup

### Clone the Repository

bash
git clone https://github.com/your-username/SmartStock.git
cd SmartStock


### Backend Setup

bash
cd backend

pip install -r requirements.txt

uvicorn main:app --reload


Backend Server:

bash
http://localhost:8000


### Frontend Setup

bash
cd frontend

npm install

npm run dev


Frontend Server:

bash
http://localhost:3000


---

## 📊 Alert Levels

| Alert Type | Description |
|------------|-------------|
| 🔴 Critical | Immediate restocking required |
| 🟡 Warning | Inventory running low |
| 🟢 Safe | Healthy stock levels |
| 🔵 Overstock | Excess inventory detected |

---

## 🔄 Workflow

1. Upload historical sales data.
2. Perform feature engineering.
3. Train or load the forecasting model.
4. Generate future demand predictions.
5. Calculate projected stock availability.
6. Trigger inventory alerts.
7. Visualize insights through the dashboard.

---

## 🧪 Testing

- ✅ Model Training & Evaluation
- ✅ API Endpoint Testing
- ✅ Dashboard Rendering
- ✅ Forecast Visualization
- 🚧 Frontend-Backend Integration
- 🚧 Notification System

---

## 🎯 Future Enhancements

- Email Alert Notifications
- SMS Alert System
- Cloud Deployment (AWS/Azure)
- Advanced Deep Learning Models
- Real-Time Inventory Tracking
- Dark Mode Support
- Multi-Warehouse Management

---

## 👨‍💻 Team

- *Vidhi Srivastava* – Team Lead
- *Chandni Maithil* – Frontend Development
- *Aditya Rajauriya* – Machine Learning Development
- *Divyanshu Yadav* – Data Engineering

---

## 📈 Business Impact

SmartStock enables businesses to:

- Reduce inventory holding costs
- Prevent stock shortages
- Improve demand planning accuracy
- Automate inventory monitoring
- Make data-driven purchasing decisions

---

## 📜 License

This project was developed as an academic Full Stack Web Development project and is intended for educational and research purposes.

---

## ⭐ Support

If you found this project useful, consider giving it a star ⭐ on GitHub.

*SmartStock – Predict Smarter. Stock Better.*
