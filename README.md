# 🚀 FinStream Engine (CardAPI Tester v3)

A next-generation **fintech API testing & transaction simulation platform** designed for high-performance systems.

This tool goes beyond traditional API clients by enabling **real-time transaction simulation, multithreading, fraud monitoring, and system-level performance analysis**.

---

## ⚠️ Distribution Note

> This repository does NOT contain the full backend source code.  
> The system is distributed using a compiled `.exe` file along with required resources.

Included in this repository:

- ✅ Executable file (`.exe`) – Main transaction engine  
- ✅ Database setup scripts (required tables)  
- ✅ PIN & PAN encryption tools (C++ source included)  
- ✅ API collection for testing  
- ✅ Frontend testing UI (hosted via GitHub Pages)

---

## ⚡ Key Features

### 🧪 API Testing (Single Mode)
- Send real-time API requests  
- JSON body editor with formatting  
- Response viewer with status & latency  
- Environment switching (DEV / UAT / PROD)  

---

### ⚡ Multi-Request Engine (Concurrency Testing)
- Execute multiple requests simultaneously  
- Configurable concurrency level  
- Real-time progress tracking  
- TPS (Transactions Per Second) calculation  
- Pipeline visualization (Queued → Processing → Done → Error)  

---

### 🏦 Multi-Channel Simulation
Supports real-world banking channels:

- 🏧 ATM (Withdrawal / Deposit)  
- 📱 Mobile Banking  
- 🏪 POS (Purchase / Refund)  
- 🌐 E-Commerce (Purchase / Refund)  
- 🃏 Card Issuer  
- 🔳 QR Payments  
- 📡 Contactless (RingPay)  

---

### 📊 Real-Time Metrics Dashboard
- Total Requests  
- Success Rate  
- Average Latency  
- Active Threads  
- Live performance graphs  

---

### 🦅 Fraud Monitoring (Falcon Inspired)
- Real-time transaction risk scoring  
- Low / Medium / High risk classification  
- Fraud activity tracking panel  

---

### 🧠 Scenario Builder
- Chain multiple API calls  
- Simulate real transaction flows  
- End-to-end testing support  

---

### 🎨 Advanced UI/UX
- Vision Pro–inspired futuristic interface  
- Fully interactive dashboard  
- Resizable panels  
- Command palette (⌘K)  
- Dark glassmorphism design  

---

## 🛠 Tech Stack

- Frontend: HTML, CSS, JavaScript  
- Backend: C++ (High-performance transaction engine)  
- Database: MySQL  
- Architecture: Multi-threaded processing engine  

---

## 🗄️ Database Setup

Before running the engine, create the following mandatory tables:

### 1. Country Currency Table
- Stores country and currency mappings  

### 2. Card Table
- PAN (Primary Account Number)  
- Expiry Date  
- Card Status  

### 3. Account Table
- Account Number  
- Balance  
- Linked Card  

> ⚠️ These tables are required for transaction execution.

---

## 🔐 Encryption Tools

The project includes utilities for secure data handling:

### 🔑 PIN Encryption Tool
- Encrypt and decrypt PIN securely  

### 💳 PAN Encryption Tool
- Encrypt and decrypt card numbers  

---

## 👨‍💻 Author & Contact

**This project is created by Rohan Avinash Sakhare.**

If you're interested in understanding how this system works, implementing it, or accessing the full source code, feel free to connect.

📧 Email: rohanavinashsakhare@gmail.com  
📱 Mobile: +91 9112765649  
💼 LinkedIn: https://www.linkedin.com/in/rohansakhareofficial/  
🌐 Portfolio: https://rohsak5649.github.io/OfficialPortfolio/  

---

## 🤝 Collaboration

Interested in this project or want to use the full system?

- For implementation guidance  
- For source code access  
- For collaboration opportunities  

👉 Please reach out directly via email, phone, or LinkedIn.

---

## 📄 License

This project is intended for **educational, simulation, and performance testing purposes only**.  
Unauthorized redistribution or reverse engineering is prohibited.
