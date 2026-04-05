# 🔗 URL Shortener (Node.js + MongoDB)

A simple and efficient URL Shortener application built using Node.js, Express, and MongoDB. It allows users to convert long URLs into short links and track their usage.

---

## 🚀 Features
- Generate short URLs
- Redirect to original URLs
- Track visit history (click analytics)
- REST API based implementation

---

## 🛠️ Tech Stack
- Node.js
- Express.js
- MongoDB
- Mongoose

---

## 📌 API Endpoints

### 1. Create Short URL
POST /url

Request Body:
{
  "url": "https://example.com"
}

Response:
{
  "id": "shortId"
}

---

### 2. Redirect to Original URL
GET /:shortId

---

### 3. Get Analytics (Optional)
GET /analytics/:shortId

---

## ⚙️ Installation

1. Clone the repository
git clone https://github.com/Vanshtyagi26/url-shortener
2. Install dependencies
npm install

3. Start the server
npm start

---

## 📂 Project Structure
- controllers/
- models/
- routes/
- connect.js
- index.js

---

## 🎯 Future Improvements
- Custom short URLs
- Frontend UI
- Deployment (Render/Netlify)
- User authentication

---

## 👨‍💻 Author
Vansh Tyagi
