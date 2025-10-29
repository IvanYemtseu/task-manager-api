# Task Manager Application (REST API)

Instructions:
This project provides a REST API for managing tasks.
Supported HTTP methods: POST, GET, PUT, DELETE.

Priority Levels:
- LOW
- MEDIUM
- HIGH

Task Status:
- TODO
- IN_PROGRESS
- DONE

---

## Interaction Examples

### 1. Create Task
POST http://localhost:8080/api/tasks
Content-Type: application/json

{
  "title": "learn spanish",
  "description": "Read a book",
  "status": "TODO",
  "priority": "HIGH"
}

---

### 2. Update Task
PUT http://localhost:8080/api/tasks/1
Content-Type: application/json

{
  "title": "learn english",
  "description": "Read a book",
  "status": "DONE",
  "priority": "HIGH"
}

---

### 3. Delete Task
DELETE http://localhost:8080/api/tasks/{taskId}

---

### 4. Get All Tasks
GET http://localhost:8080/api/tasks

---

### 5. Get Tasks by Status
GET http://localhost:8080/api/tasks/status/{TODO}

---

Author:
[github.com/IvanYemtseu](https://github.com/IvanYemtseu)
