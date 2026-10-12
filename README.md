# AI Interview Prep 🎯

An AI-powered interview preparation platform designed to help candidates practise interviews, receive personalized feedback, and improve their interview performance.

## ✨ Features

- **AI-Powered Interview Practice** — Practise interview questions with AI assistance.
- **User Authentication** — Register and log in securely.
- **Resume Analysis** — Upload a PDF resume and extract its text for interview preparation.
- **Interview Reports** — Review feedback and performance summaries.
- **Interview Dashboard** — Access interview preparation features through a web interface.

## 🛠️ Tech Stack

**Frontend**
- React
- Vite
- JavaScript
- SCSS

**Backend**
- Node.js
- Express.js
- MongoDB
- Mongoose

**AI & Utilities**
- Google Gemini API
- PDF parsing
- JWT authentication
- bcryptjs

## 📁 Project Structure

```text
ai-interview-prep/
├── Backend/
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── middlewares/
│   │   ├── models/
│   │   ├── routes/
│   │   └── services/
│   ├── app.js
│   └── server.js
├── Frontend/
│   ├── public/
│   └── src/
└── .gitignore
```

## ⚙️ Getting Started

### Prerequisites

- Node.js and npm
- MongoDB connection
- Google Gemini API key

### 1. Clone the repository

```bash
git clone https://github.com/krishnitwal/ai-interview-prep.git
cd ai-interview-prep
```

### 2. Set up the backend

```bash
cd Backend
npm install
```

Create a `.env` file in the `Backend` directory and configure the environment variables required by the application, such as your MongoDB connection string, JWT secret, and Gemini API key.

Start the backend:

```bash
npm run dev
```

### 3. Set up the frontend

Open another terminal:

```bash
cd Frontend
npm install
npm run dev
```

Open the local URL shown by Vite in your terminal.

## 🔐 Security

Never commit API keys, database credentials, JWT secrets, or other sensitive environment variables to GitHub.

## 👨‍💻 Author

**Krish Nitwal**

GitHub: [@krishnitwal](https://github.com/krishnitwal)

---

*Built to make interview preparation more structured, accessible, and effective.*
