# 🔐 AI/ML: Real-Time Fraud Detection in Banking Transactions

A real-time, full-stack fraud detection system using Machine Learning and SMS-based risk signals to flag suspicious banking transactions with sub-300ms latency.

---

## 🌐 Live Demo
[Live Link](#)

## 🧠 Code Repositories
- **ML Model**: [github.com/abhinn14/fraudy](https://github.com/abhinn14/fraudy)
- **Backend API**: [github.com/abhinn14/fraud_detect](https://github.com/abhinn14/fraud_detect)
- **Frontend (React Native)**: [github.com/ittou-shura/fiddy](https://github.com/ittou-shura/fiddy)

---

## 🚀 Features

- **⚙️ ML-Powered Fraud Detection**  
  Trained and deployed models using **XGBoost**, **Isolation Forest**, and a custom **Neural Network**, achieving **94% precision** in detecting fraudulent banking activity.

- **📩 SMS-Based Risk Signals**  
  Parsed the **latest 10 SMS messages** to extract risk features such as:
  - Transaction alerts
  - Suspicious keywords (e.g., "OTP", "blocked", "limit exceeded")
  - OTP patterns and sender reputation  
  Resulted in an **~12% boost in accuracy** by incorporating contextual signals.

- **⚡ Real-Time Detection Pipeline**  
  Designed a fast-response backend that flags suspicious transactions in **under 300ms**, using features such as:
  - Transaction amount  
  - Timestamp and frequency  
  - IP address and location mismatches

- **🔒 Proactive User Alert System**  
  Users are instantly notified if a transaction or message shows signs of fraud, enabling early prevention and security awareness.

---

## 🧰 Tech Stack

| Layer       | Tools & Frameworks                         |
|-------------|--------------------------------------------|
| Frontend    | React Native, Zustand, Tailwind CSS        |
| Backend     | Node.js, Express.js, JWT, WebSockets       |
| ML Models   | Python, Scikit-learn, XGBoost, TensorFlow  |
| Dev Tools   | Git, GitHub, Postman, Linux                |

---

## 📷 Screenshots
> (Add 2-3 screenshots or demo GIFs here to show UI, predictions, and alerts)

---

## 📈 Future Improvements
- SMS sender reputation scoring
- UI for user feedback on false positives
- Dockerized deployment
- Model retraining with online learning

---

## 📄 License
MIT License © 2025 [Your Name]
