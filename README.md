# Y.task 📝 ⏳ 📅

### Welcome to Y.task !!!

**Y.task** is a **Task Management Application** where users can add, edit, delete, and categorize tasks into To-Do, In Progress, and Done sections. The backend is built using Node.js, Express, and MongoDB to provide a RESTful API for task management.

## 🔗 Live Links:

- https://job-task-50885.web.app
- https://job-task-50885.firebaseapp.com

## 📦 Dependencies:

The following dependencies are used in this project:

- "cors": "^2.8.5",
- "dotenv": "^16.4.7",
- "express": "^4.21.2",
- "mongodb": "^6.13.1"

## 🛠️ Setup & Installation:

Follow these steps to run the project locally:

### 1️⃣ Clone the Repository:

```
git clone https://github.com/Motiur-Rahman-Dhrubo/job-task-server
cd job-task-server
```

### 2️⃣ Install Dependencies:

```
npm install
```

### 3️⃣ Set Up Environment Variables:

- Create a .env file in the root directory.
- Add the following variables:

```
DB_USER=job_user
DB_PASS=qt5RNOiarVoZ4nKl
```

### 4️⃣ Run the Server:"

```
nodemon index.js
```

The server should be running on http://localhost:5000

## 🛠️ Technologies Used:

- Node.js - JavaScript runtime
- Express.js - Backend framework
- MongoDB - NoSQL database
- Cors - Middleware for handling CORS
- Dotenv - Environment variable management

## 📌 Core Features:

✅ Add new tasks <br>
✅ Edit tasks <br>
✅ Delete tasks <br>
✅ Categorize tasks into different sections <br>
✅ API with RESTful endpoints <br>
✅ Persistent data storage using MongoDB