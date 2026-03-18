# 🚀 Google Gemini API Chatbot

A simple Node.js + Express application that integrates Google Gemini API to generate AI responses with a clean and modern chat UI.

---

## Tech Stack:

- Node.js
- Express.js
- Google Generative AI SDK
- HTML, CSS, JavaScript

---

## Setup Instructions:
```bash
### 1. Clone the repo:
git clone https://github.com/your-username/google-gemini-api.git
cd google-gemini-api

### 2. Install dependencies:
npm install

### 3. Add your API key:
In app.js:
const genAI = new GoogleGenerativeAI("YOUR_API_KEY");

### 4. Run the Project:
node app.js
Server runs at: http://localhost:3000
```

---

## How It Works?

- User types message in UI
- Request sent to backend
- Gemini API generates response
- Response shown in chat

---

## Notes:

- Keep your API key private
- Use .env for production