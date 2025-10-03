🛒 Product CRUD System
📘 Overview

This is a Product Management System built with Node.js, Express.js, and MongoDB (Mongoose).
It supports full CRUD operations with validation and error handling.

Each product has:

🏷️ name (String, required)

💰 price (Number, required, must be >= 0)

📂 category (String, required)

⚙️ Features

➕ Add a new product

📖 Get all products

🔍 Get a product by ID

✏️ Update a product by ID

❌ Delete a product by ID

💾 Installation & Run

1️⃣ Clone the project and open folder
2️⃣ Install dependencies

npm install express mongoose body-parser nodemon


3️⃣ Make sure MongoDB is running
4️⃣ Start the server

npx nodemon server.js

📌 API Endpoints

➕ POST /products → Create a product

📖 GET /products → Get all products

🔍 GET /products/:id → Get product by ID

✏️ PUT /products/:id → Update product by ID

❌ DELETE /products/:id → Delete product by ID

🛠️ Tech Stack

⚡ Node.js

🚀 Express.js

🍃 MongoDB + Mongoose

🔄 Nodemon
