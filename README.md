# MagicStream 🎬✨

**MagicStream** is a high-performance, full-stack movie streaming simulation. It features an **AI-powered recommendation engine** that analyzes user sentiment to suggest films, showcasing a modern architecture built with Go, React, and MongoDB.

---

## 🚀 Overview

This project demonstrates a production-ready approach to building a media platform. It bridges the gap between traditional web services and modern AI, utilizing **LangChainGo** to personalize the user experience based on real-time feedback and sentiment analysis.

### Core Features
* **AI Recommendations:** Integrated with OpenAI and LangChainGo to process movie reviews and suggest top-rated content dynamically.
* **High-Speed API:** Backend built with Go (Golang) and the Gin framework for low-latency requests.
* **Responsive UI:** A sleek, mobile-friendly interface built with React, Vite, and Bootstrap.
* **Secure Authentication:** Implements JWT authentication with HTTP-only cookies to protect against XSS attacks.
* **Simulated Playback:** Seamless video simulation using `react-player`.

---

## 🛠 Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend** | React, Vite, React-Bootstrap, Axios |
| **Backend** | Go (Golang), Gin-Gonic |
| **AI Engine** | LangChainGo, OpenAI API |
| **Database** | MongoDB (Atlas) |
| **Authentication** | JWT (JSON Web Tokens) |

---

## ⚙️ Installation & Setup

### Prerequisites
* [Go](https://golang.org/doc/install) (v1.20+)
* [Node.js](https://nodejs.org/) (v18+)
* [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) account
* [OpenAI API Key](https://platform.openai.com/)

### 1. Clone the Repository
```bash
git clone [https://github.com/YOUR_GITHUB_USERNAME/MagicStream.git](https://github.com/YOUR_GITHUB_USERNAME/MagicStream.git)
cd MagicStream
2. Backend Configuration
Create a .env file in your backend folder:

Code snippet

PORT=8080
MONGODB_URI=your_mongodb_connection_string
OPENAI_API_KEY=your_openai_api_key
JWT_SECRET=your_secret_key
Run the backend:

Bash

# Navigate to backend directory
cd server 
go run main.go
3. Frontend Configuration
Navigate to the frontend directory and install dependencies:

Bash

# Navigate to frontend directory
cd client
npm install
npm run dev
📺 Video Tutorial
This project was inspired by and built following this comprehensive guide:

📝 License
Distributed under the MIT License. See LICENSE for more information.
