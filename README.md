# Piyush's To-Do List App
Note- Make sure you Extract the projet first from this zip file before trying to run it!!
A full-stack MERN (MongoDB, Express, React, Node.js) To-Do List application with user authentication, user-specific tasks, and persistent storage in MongoDB.

## Features
- User registration with username, password, age, mobile number, email, and gender
- Secure login with JWT authentication
- Each user sees only their own tasks
- Add, edit, complete, and delete tasks
- Responsive and modern UI

## Getting Started

### 1. Clone or Download the Repository
If you have a zipped folder, extract it. If you uploaded to GitHub, clone it:
```sh
git clone <your-repo-url>
cd To-Do-List
```

### 2. Install Dependencies
#### Backend
```sh
cd backend
npm install
```
#### Frontend
```sh
cd ..
npm install
```

### 3. Start MongoDB
Make sure MongoDB is running locally on the default port (27017).

### 4. Run the Backend
```sh
cd backend
npm run dev
```
The backend will start on http://localhost:5000

### 5. Run the Frontend
In a new terminal:
```sh
npm run dev
```
The frontend will start on http://localhost:5173 (or similar, check your terminal output).

### 6. Open the App
Go to [http://localhost:5173](http://localhost:5173) in your browser.

## Usage
- Register a new user with all required fields
- Login with your username and password
- Add, edit, complete, and delete your tasks
- Each user only sees their own tasks

## Notes
- Make sure MongoDB is running before starting the backend
- The backend uses `mongodb://localhost:27017/todo-list` by default
- You can view your data in MongoDB Compass under the `todo-list` database

---

**Enjoy using Piyush's To-Do List App!**

