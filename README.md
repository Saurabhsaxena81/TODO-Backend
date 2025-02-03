# 📝 Simple To-Do App Backend

This is a lightweight backend for a **To-Do App**, built using **Node.js and Express**. It provides basic functionalities to **add and delete to-dos**, making task management seamless and efficient.

## 🚀 Features
- ✅ Add new to-dos
- ✅ Delete existing to-dos
- ✅ Retrieve all to-dos
- ✅ Basic error handling for better stability
- ✅ CORS enabled for smooth frontend integration
- ✅ Lightweight and easy to deploy

## 🛠 Tech Stack
- **Backend:** Node.js, Express.js
- **Database:** MongoDB & Mongoose (if used)
- **Middleware:** CORS for cross-origin requests

## 📌 Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Saurabhsaxena81/todo-app-backend.git
   cd todo-app-backend
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Create a `.env` file** in the root directory and add the following environment variables (if using MongoDB):
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   ```

4. **Start the server:**
   ```sh
   npm start
   ```

## 📡 API Endpoints

### 📝 To-Dos
- `GET /api/todos` - Retrieve all to-dos
- `POST /api/todos` - Add a new to-do
- `DELETE /api/todos/:id` - Delete a to-do by ID

## 📂 Folder Structure
```
📂 todo-app-backend
 ┣ 📂 models
 ┃ ┗ 📜 Todo.js         # Todo model (if using MongoDB)
 ┣ 📂 routes
 ┃ ┗ 📜 todoRoutes.js   # To-do management routes
 ┣ 📂 config
 ┃ ┗ 📜 db.js           # Database connection setup
 ┣ 📜 .env.example      # Example environment variables
 ┣ 📜 server.js         # Main server file
 ┣ 📜 package.json      # Dependencies and scripts
```

## 📦 Dependencies
- express - Minimalist web framework
- cors - Enables CORS for frontend communication
- mongoose (if using MongoDB) - ODM for MongoDB
- dotenv - Manage environment variables
--

## 🔮 Future Enhancements
- 🌟 Implement a database for persistent storage
- 📌 Add task update functionality
- 🛡️ Improve input validation and error handling
- 📊 Integrate logging for better debugging

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).

---
💡 Feel free to contribute or suggest improvements!
