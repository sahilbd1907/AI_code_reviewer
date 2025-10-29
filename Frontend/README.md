# 🤖 AI-Powered Code Reviewer

An intelligent full-stack web application that provides **instant AI-based code reviews** to help developers write cleaner, more efficient, and more secure code.  
Built using **React.js**, **Node.js**, **Express.js**, and **Google Gemini AI**.

---

## 🌐 Overview

This project allows users to paste or write code in a web-based editor and receive **real-time AI-generated feedback** on:
- Code quality and readability  
- Best practices and structure  
- Performance and scalability  
- Maintainability and security  

---

## ⚙️ Tech Stack

**Frontend:** React.js, Vite, HTML, CSS  
**Backend:** Node.js, Express.js  
**AI Engine:** Google Gemini Generative AI API  
**Database:** MongoDB (optional, for storing review logs or user sessions)

---

## 🧩 Features

- 🧠 **AI Code Review:** Get structured, human-like code feedback instantly.  
- 💻 **Interactive Editor:** Syntax-highlighted code input panel.  
- ⚡ **Fast Processing:** Uses efficient API routing and Vite for quick builds.  
- 🔐 **Secure API Communication:** Handles validation and sanitization.  
- 🧩 **Modular Architecture:** Clear separation of services, routes, and controllers.  

---


---

## 🧭 Workflow

1. User writes or pastes code in the editor.  
2. User clicks **“Review”** to submit the code.  
3. Backend API (`/ai/get-review`) sends the code to **Google Gemini AI**.  
4. Gemini analyzes the code and generates a professional review.  
5. The review is returned and displayed in the frontend UI.  

---

## 🛠️ Installation and Setup

### Prerequisites
- Node.js (v18+)
- npm or yarn
- Google Gemini API key

### 1️⃣ Clone the Repository
git clone https://github.com/yourusername/AI-Code-Reviewer.git
cd AI-Code-Reviewer

### 2️⃣ Backend Setup
cd Backend
npm install
Create a .env file inside the Backend directory:
GEMINI_API_KEY=your_google_gemini_api_key
PORT=5000
Run the backend server:
npm start

### 3️⃣ Frontend Setup
cd ../Frontend
npm install
npm run dev


Frontend runs on:
👉 http://localhost:5173

---

## 📜 License

This project is licensed under the MIT License — feel free to use and modify it for your learning or portfolio.