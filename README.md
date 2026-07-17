# MERN ToDo Application

A full-stack ToDo List application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) with Tailwind CSS for a modern and responsive user interface. The application allows users to create, view, update, and delete tasks through RESTful APIs.

---

## Features

- Create new tasks
- View all tasks
- Update existing tasks
- Delete tasks
- Responsive user interface
- RESTful API architecture
- MongoDB database integration
- Real-time UI updates
- Clean and reusable React components

---

## Tech Stack

### Frontend

- React.js
- Tailwind CSS
- Axios
- Vite

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose

---

## Project Structure

```
mern-todo-app/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── config/
│   └── package.json
│
├── README.md
└── .gitignore
```

---

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /tasks | Get all tasks |
| POST | /tasks | Create a new task |
| PUT | /tasks/:id | Update a task |
| DELETE | /tasks/:id | Delete a task |

---

## Installation

### Clone Repository

```bash
git clone https://github.com/SatyawanXsingh/mern-todo-app.git
```

### Backend

```bash
cd backend
npm install
npm run dev
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## Environment Variables

Create a `.env` file inside the backend directory.

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
```

---

## Screenshots

Add screenshots of the following pages:

- Home Page
- Add Task
- Update Task
- Delete Task

---

## Future Improvements

- User Authentication
- Task Categories
- Due Dates
- Task Priorities
- Search & Filter
- Dark Mode
- Drag & Drop Task Ordering
- Notifications

---

## Learning Outcomes

- MERN Stack Development
- REST API Development
- MongoDB CRUD Operations
- React Hooks
- Axios API Integration
- Express.js Routing
- State Management
- Tailwind CSS
- Component-Based Architecture

---

## License

This project is developed for learning purposes.
