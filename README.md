# 🛡️ JoFraud Lab - CBJ Compliance Ready Fraud Monitoring

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![AI](https://img.shields.io/badge/AI-Gemini_API-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Live_Demo-brightgreen?style=for-the-badge)

> Real-time fraud detection dashboard simulating Jordanian banking transactions (CliQ, Visa, IBAN) with AI-powered AML analysis.

**🔗 Live Demo:** https://claude.ai/public/artifacts/4f37e448-9ebf-4df7-8fa0-ed907d915543

### 🚀 Key Features
- 📊 50 Simulated Transactions - Jordan-focused with CliQ, Card, IBAN
- 🚨 Fraud Detection Engine - Risk scoring based on foreign + odd hour + large amount
- 💰 Business Impact: Detected 6 fraud cases (12% rate) - Saved 49,836 JOD
- 🔍 Detailed Investigation Modal - Shows Customer ID, Device, IP, Location Mismatch
- 🇯🇴 CBJ Compliance - Auto-flags transactions >10,000 JOD
- 🤖 AI Risk Analysis - Bilingual AML alerts (Arabic & English)
- 📤 Dynamic Data - Upload new CSV and recalculates instantly

### 🧠 How Risk Scoring Works
Risk = foreign country (40) + odd hour (30) + large amount (20) + Visa (10)
If risk >= 75 => Fraud

### 🛠️ Tech Stack
React + Tailwind CSS + Recharts + Gemini API + Claude

### 👨‍💻 Author
Yousef Qasrrawi - AI in Financial Services - Built entirely on mobile
