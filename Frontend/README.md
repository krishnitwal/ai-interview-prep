# AI Interview Prep

An AI-powered interview preparation platform designed to help candidates practise interviews, receive feedback, and improve their interview skills.

## Features

- **AI-powered interview practice** — practise interview questions with AI assistance.
- **User authentication** — registration and login.
- **Interview reports** — review feedback and performance summaries.
- **Interview preparation dashboard** — access interview practice features through a web interface.

## Tech Stack

**Frontend:** React, Vite, JavaScript, SCSS  
**Backend:** Node.js, Express.js  
**Database:** MongoDB with Mongoose  
**AI Integration:** Google Gemini API

## Getting Started

### Prerequisites

- Node.js and npm
- MongoDB connection
- Google Gemini API key, if required by the AI features

### Installation

Clone the repository:

```bash
git clone https://github.com/krishnitwal/ai-interveiw-prep.git
cd ai-interview-prep
```

Install backend dependencies:

```bash
cd Backend
npm install
```

Configure your environment variables using a local `.env` file. Never commit API keys, database credentials, or JWT secrets.

Start the backend using the script defined in `Backend/package.json`.

In a separate terminal, install the frontend dependencies:

```bash
cd Frontend
npm install
npm run dev
```

## Project Status

Under development. Setup instructions and features may change as the project evolves.

## Attribution

This project is based on an existing open-source project. Original authors and license information should be retained and credited according to the original repository's license.

## Author Contributions

Add your own contributions here as you implement and test them.
