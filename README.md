# Google_Sheet

A full-stack Google Sheets-like spreadsheet application built with React, TypeScript, Express, and MongoDB.

🚀 Features

User authentication (Sign-up & Sign-in)

Create, edit, and delete sheets

Collaborative editing

Dynamic grid system

Save and load data from MongoDB

🛠 Tech Stack

Frontend:

React.js (Vite + TypeScript)

Tailwind CSS

Axios

Backend:

Node.js + Express.js

TypeScript

MongoDB + Mongoose

JSON Web Token (JWT) for authentication

📂 Folder Structure

/google-sheets-clone
 ├── client/         # Frontend (React)
 ├── server/         # Backend (Node.js + Express)
 ├── README.md       # Project documentation
 ├── .env.example    # Environment variables (example file)
 ├── package.json    # Dependencies & scripts

📦 Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/your-username/google-sheets-clone.git
cd google-sheets-clone

2️⃣ Backend Setup

cd server
npm install

Create a .env file in the server directory and add:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

Start the backend:

npm run dev

3️⃣ Frontend Setup

cd client
npm install

Start the frontend:

npm run dev

The app should be running at http://localhost:3000 🚀

🔧 API Endpoints

Auth Routes

POST /api/user/sign-up → Register a new user

POST /api/user/sign-in → Authenticate user

Sheets Routes

POST /api/sheet/create → Create a new sheet

GET /api/sheet/:id → Fetch sheet data

DELETE /api/sheet/:id → Delete a sheet
