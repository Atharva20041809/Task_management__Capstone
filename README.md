# Task Management System

## Project Overview
This project is a Task Management System that allows users to manage their daily tasks efficiently. Users can create, view, update, and delete tasks. The system follows a full-stack architecture with a frontend, backend, and database.

---

## Features

### User Authentication
- Signup
- Login

### Task Management
- Add Task
- View Tasks
- Update Task
- Delete Task

---

## Tech Stack

### Frontend
- React.js
- HTML, CSS, JavaScript

### Backend
- Node.js
- Express.js
- TypeScript

### Database
- MongoDB

---

## System Architecture

The system is divided into multiple layers:

1. Frontend (React)
   - Handles UI and user interactions

2. Backend (Express API)
   - Handles API requests and responses

3. Service Layer
   - Contains business logic

4. Database (MongoDB)
   - Stores user and task data

---

## UML Diagrams

- Class Diagram
- Sequence Diagram (Add Task, Get Tasks)
- Use Case Diagram
- ER Diagram (Crow’s Foot & Chen Notation)

---

## API Endpoints

### Task APIs

- POST /addTask  
  Adds a new task

- GET /getTasks  
  Retrieves all tasks

- PUT /updateTask  
  Updates a task

- DELETE /deleteTask  
  Deletes a task

---

## Data Model

### User
- userId
- username
- email
- password

### Task
- taskId
- title
- description
- status
- createdAt
- userId (reference to User)

---
