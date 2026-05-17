📦 agentic-layout

A simple AI-powered Layout Agent application built with React (frontend) and Node.js + Express (backend).
It allows users to send messages and get AI-processed responses to dynamically manage or generate layout ideas.

🚀 Features
💬 Chat-style message system
⚡ Real-time API communication
🧠 Backend message processing (Express server)
🎯 Clean React UI with hooks-based state management
🌐 CORS-enabled frontend-backend integration
🛠️ Tech Stack
Frontend:
React.js
JavaScript (ES6+)
Fetch API
Backend:
Node.js
Express.js
CORS
dotenv
📁 Project Structure
agentic-layout/
│
├── frontend/
│   ├── src/
│   │   ├── App.js
│   │   ├── hooks/useLayoutAgent.js
│   │   └── utils/api.js
│
├── backend/
│   ├── server.js
│   ├── routes/chat.js
│
├── package.json
└── README.md
⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/Kanchanbhosle/agentic-layout.git
cd agentic-layout
2️⃣ Install backend dependencies
cd backend
npm install
3️⃣ Start backend server
node server.js

Server runs on:

http://localhost:3001
4️⃣ Install frontend dependencies
cd frontend
npm install
5️⃣ Start frontend
npm start

App runs on:

http://localhost:3000
🔗 API Endpoint
POST /chat

Request:

{
  "message": "Hello"
}

Response:

{
  "reply": "Processed: Hello"
}
🧠 How It Works
User types a message in UI
Frontend sends request to backend (/chat)
Backend processes message
Response is sent back to frontend
UI updates with assistant reply
🧪 Example
User: Hello
Bot: Processed: Hello 
