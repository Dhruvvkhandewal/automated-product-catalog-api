# 🚀 Automated Deployment Pipeline for Node.js Product Catalog API

This project demonstrates how to build and deploy a **Node.js-based Product Catalog API** with a fully automated **CI/CD pipeline** using **GitHub Actions** and **Docker**. The API allows users to manage product data — create, update, delete, and view product information — making it a scalable backend for e-commerce or inventory systems.

---

## 🧩 Key Features
- **Node.js + Express:** Fast, lightweight RESTful API.  
- **Dockerized Environment:** Ensures consistent builds and deployments.  
- **GitHub Actions CI/CD:** Automates testing, building, and deployment.  
- **Scalable Architecture:** Easily extendable with authentication, database, or caching layers.  
- **Error Handling:** Built-in middleware for better debugging and stability.  

---

## ⚙️ Tech Stack
- **Backend:** Node.js (v18+), Express.js  
- **Automation:** GitHub Actions  
- **Containerization:** Docker  
- **Deployment Options:** Render, Railway, AWS Elastic Beanstalk, or any Docker-compatible host  

---

## 🧱 Folder Structure
product-catalog/
├── server.js # Main API file
├── package.json # Dependencies & scripts
├── Dockerfile # Docker build configuration
└── .github/
└── workflows/
└── deploy.yml # CI/CD workflow

---

## 🔄 CI/CD Workflow Overview
**Trigger:** Runs automatically on push to the `main` branch.  
**Steps:**  
1. Checkout source code  
2. Setup Node.js environment  
3. Install dependencies  
4. Run tests (optional)  
5. Build and package Docker image  
6. Deploy automatically to target platform  

This ensures that each commit is tested, built, and deployed without manual effort — improving reliability and reducing release time.

---

## 🧰 Run Locally
```bash
npm install
npm start
docker build -t product-catalog .
docker run -p 3000:3000 product-catalog
👨‍💻 Author

Dhruv Khandelwal
🌐 GitHub
 • 💼 LinkedIn
