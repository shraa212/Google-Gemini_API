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

### 1. Clone the repo:
```bash
git clone https://github.com/your-username/google-gemini-api.git
cd google-gemini-api
```
### 2. Install dependencies:
```bash
npm install
```
### 3. Add your API key:
```bash
In app.js:
const genAI = new GoogleGenerativeAI("YOUR_API_KEY");
```
### 4. Run the Project:
```bash
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