Blog API – Express & Node.js (No Database)

A simple and lightweight RESTful Blog API built using Node.js and Express.js, designed for learning, prototyping, and small demo applications.
This project uses in-memory storage, meaning all blog data is stored temporarily in variables/arrays without using any database.

🚀 Features

⚡ No Database Required – Data stored in memory

📝 Full CRUD operations for blog posts

🔄 Auto-refreshing/resetting data on server restart

🧩 Clean & modular Express structure

🌐 CORS enabled for cross-origin access

🧪 Great starter backend for learning REST APIs

📚 API Endpoints
POST   /api/posts        → Create a new blog post  
GET    /api/posts        → Get all blog posts  
GET    /api/posts/:id    → Get single post  
PUT    /api/posts/:id    → Update a post  
DELETE /api/posts/:id    → Delete a post

🛠️ Tech Stack

Node.js

Express.js

(No database — in-memory array used for data)

🏁 Getting Started

Clone the repository

Run npm install

Start server with node server.js or npm run dev

Use Postman/Thunder Client to test your API

🎯 Use Cases

Beginners learning APIs

Demo projects

Testing frontend apps without backend setup

Temporary mock backend
