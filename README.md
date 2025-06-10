# 📸 Pixisphere Backend

Welcome to the **Pixisphere Backend** – a mock REST API created using [JSON Server](https://github.com/typicode/json-server). This backend powers the frontend for a photography listing platform, providing endpoints for photographers, categories, and more.

---

## 🔧 Tech Stack

- **Node.js**
- **JSON Server**
- **Express.js** (optional, for customization)
- **Render** (for deployment)

---

## 📁 Project Structure

pixisphere-backend/
│
├── db.json # Main mock database
├── routes.json # Custom routes (optional)
├── server.js # Optional custom server using Express
├── package.json # Project config & dependencies
└── README.md # Project documentation
2. Install Dependencies
bash
Copy
Edit
npm install
3. Run the Server
Option 1: Run with JSON Server directly
bash
Copy
Edit
npx json-server --watch db.json --port 10000
Option 2: Run with a Custom Server (if using Express)
bash
Copy
Edit
node server.js
✅ By default, the server runs on: http://localhost:10000/
📜 License
This project is licensed under the MIT License.

