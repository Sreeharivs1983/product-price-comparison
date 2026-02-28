# 🛍️ Product Price Comparison Application

A cloud-native microservices application that compares product prices across different dealers.  
This project demonstrates containerization, microservices architecture, and serverless deployment using IBM Cloud Code Engine.

---

## 🚀 Live Architecture

The application consists of:

- **Product Microservice (Python / Flask)**
- **Dealer Microservice (Node.js / Express)**
- **Frontend Web Application (HTML / JavaScript)**
- **Containerized using Docker**
- **Deployed on IBM Cloud Code Engine**

---

## 🏗️ Architecture Overview

Frontend (Code Engine)
│
▼
┌───────────────┐ ┌────────────────┐
│ Product API │ │ Dealer API │
│ (Flask) │ │ (Node.js) │
└───────────────┘ └────────────────┘
│
▼
Container Registry (ICR)




---

## 🧩 Microservices

### 1️⃣ Product Service
- Built with Python (Flask)
- Returns product details
- Deployed as: `prodlist`

### 2️⃣ Dealer Service
- Built with Node.js (Express)
- Returns dealer pricing
- Deployed as: `dealerdetails`

### 3️⃣ Frontend
- Built using HTML + JavaScript
- Fetches data from both backend APIs
- Deployed as: `frontend`

---

## 🐳 Containerization

Each service is:

- Packaged using Docker
- Built using Dockerfile
- Pushed to IBM Container Registry
- Deployed using IBM Cloud Code Engine

---

## ☁️ Deployment Platform

- IBM Cloud Code Engine
- Serverless container execution
- Auto-scaling
- Managed infrastructure

---

## 🔧 Technologies Used

- Python (Flask)
- Node.js (Express)
- HTML / JavaScript
- Docker
- IBM Cloud Code Engine
- IBM Container Registry

---

## 📦 How It Works

1. Frontend loads product list.
2. User selects a dealer.
3. Frontend calls Dealer API.
4. Combined data is displayed dynamically.

---

## 📸 Features

✔ Microservices architecture  
✔ Serverless container deployment  
✔ Cloud-native design  
✔ Auto-scaling backend  
✔ REST API integration  

---

## 🧠 What I Learned

- Designing microservices architecture
- Containerizing applications with Docker
- Building and deploying to IBM Cloud Code Engine
- Managing multiple backend services
- Integrating frontend with deployed APIs

---

## 📌 Author

Sreehari VS  
GitHub: https://github.com/Sreeharivs1983

---

