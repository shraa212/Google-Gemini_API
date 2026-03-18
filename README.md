# 🚀 Google Gemini API Chat App

A simple Node.js + Express application that integrates Google Gemini API to generate AI responses with a clean and modern chat UI.

---

## 📌 Features

- 💬 Interactive chat interface
- ⚡ Fast responses using Gemini 1.5 Flash
- 🎨 Modern glassmorphism UI
- 🔌 Simple Express backend
- 🌐 REST API for AI responses

---

## 🛠️ Tech Stack

- Node.js
- Express.js
- Google Generative AI SDK
- HTML, CSS, JavaScript

---

## 📁 Project Structure
google-gemini-api/
│── node_modules/
│── app.js
│── package.json
│── package-lock.json

---

## ⚙️ Setup Instructions

### 1. Clone the repo
```bash
git clone https://github.com/your-username/google-gemini-api.git
cd google-gemini-api
2. Install dependencies
npm install
3. Add your API key

In app.js:

const genAI = new GoogleGenerativeAI("YOUR_API_KEY");
▶️ Run the Project
node app.js

Server runs at:

http://localhost:3000
🌐 API Routes
1. Home (UI)
GET /

Opens chat interface

2. Generate Content
GET /generate-content?prompt=your_text
Example:
http://localhost:3000/generate-content?prompt=Explain%20AI
🧠 How It Works

User types message in UI

Request sent to backend

Gemini API generates response

Response shown in chat

⚠️ Notes

Keep your API key private

Use .env for production

This is a beginner-friendly project

🚀 Future Improvements

Add chat memory

Switch GET → POST

Add authentication

Store chat history

Deploy online

👩‍💻 Author

Shravani Vetal