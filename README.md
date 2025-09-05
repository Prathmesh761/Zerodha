# StockPilot 🚀  
A Zerodha-like stock trading web application built with the **MERN stack**.  
StockPilot allows users to buy/sell stocks, track their portfolio, and analyze market performance in real-time.

---

## 📌 Features
- 🔐 User Authentication (JWT-based login/signup)  
- 💹 Real-time stock data visualization (candlestick & line charts)  
- 📈 Buy/Sell functionality with virtual wallet balance  
- 🗂️ Portfolio management with profit/loss tracking  
- 📊 Dashboard with market trends and analytics  
- 🌐 Responsive UI (works on desktop & mobile)  

---

## 🛠️ Tech Stack
- **Frontend:** React.js, Redux, Tailwind CSS / Material-UI  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (Mongo Atlas)  
- **Authentication:** JWT & bcrypt  
- **API Integration:** Stock market APIs (e.g., Alpha Vantage / Yahoo Finance)  

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/stockpilot.git
# Install server dependencies
cd backend
npm install

# Install client dependencies
cd ../frontend
npm install
# Backend
PORT=5000
MONGO_URI=your_mongodb_connection_string

# Frontend
REACT_APP_API_URL=http://localhost:5000
# Run backend
cd backend
npm run dev

# Run frontend
cd ../frontend
npm start

cd stockpilot

