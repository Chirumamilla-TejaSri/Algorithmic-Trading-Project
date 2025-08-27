# 🚀 Algo-Trading-Project

## 📌 Overview
This project is an **AI-powered algorithmic trading system** designed to help traders make **timely, data-driven decisions** in volatile markets.  
Traditional manual analysis of stock trends is **time-consuming, error-prone, and lacks real-time insights**. Our solution provides an **integrated trading dashboard** with stock predictions, news sentiment, and AI-driven recommendations.

---

## ❗ Problem Statement
- Traders struggle to make timely and informed decisions due to complex market data and volatility.  
- Existing platforms lack **AI-driven insights** for actionable stock predictions and recommendations.  
- Manual analysis of stock trends is error-prone, making it hard to consistently identify profitable opportunities.  

---

## ⚡ Proposed Solution
A **web-based trading dashboard** that combines multiple features into one platform:

- 📈 **Stock Predictions** – Real-time **LSTM-based forecasts** of stock prices.  
- 📰 **News & Sentiment Analysis** – Automated fetching and labeling of market news as Positive / Negative / Neutral.  
- 🤖 **Recommendations** – Simple **BUY / HOLD / SELL** signals based on AI insights.  
- 📊 **Interactive Dashboard** – Portfolio summary, visualizations, charts, and easy navigation.  

---

## 🛠️ Technology Stack
- **Frontend:** React.js, Lottie Animations, React Icons  
- **Backend:** Flask API  
- **Database & Authentication:** Firebase Authentication & Firestore  
- **AI/ML:** Python, TensorFlow (LSTM), Scikit-learn, MinMaxScaler  
- **APIs:** Yahoo Finance, NewsAPI  

---

## 🏗️ System Architecture
- Inputs: Economic indicators, company performance, events, and news  
- Processing: LSTM prediction + sentiment analysis  
- Outputs: Stock forecasts, sentiment tags, and recommendations  
- Display: Web dashboard with portfolio and charts  

---

## 🔹 Key Features
- 📊 **LSTM-based Stock Predictions** with technical indicators (MA_10, EMA_10)  
- 📰 **News & Sentiment Analysis** using NLP (Positive / Negative / Neutral)  
- 🤖 **AI-driven Recommendations** (Buy / Hold / Sell)  
- 📈 **Interactive Charts & Portfolio Summary**  

---

## 🧠 AI Model Workflow
1. **Data**: Stock Close, Volume, MA_10, EMA_10  
2. **Preprocessing**: Normalization with MinMaxScaler  
3. **Sequence Creation**: 90-day rolling window  
4. **Model**: LSTM → Dropout → Dense layers  
5. **Output**: Predicted price & % change → Recommendation generation  

---

## ✅ Advantages / Benefits
- Real-time insights for **smarter trading decisions**  
- Integrated platform – all data in one place  
- AI-driven recommendations reduce manual errors  
- User-friendly interface with clear visualizations  
- Scalable & extendable for more stocks or features  

---

## 🚀 Future Work
- Add support for **more stocks and indices**  
- Improve prediction accuracy with advanced features  
- Develop a **mobile-friendly version**  
- Enable **portfolio performance tracking with alerts**  

---

## 👩‍💻 Team
**Collaborative Crew**  
- Chirumamilla Teja Sri  
- Chouturi Susmitha  
- Andela Ramesh  
- Katta Sushma Sree  
