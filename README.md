# Task manager application (REST API)
Instructions:
You have POST GET PUT DELETE commands
Priority levels: LOW, MEDIUM, HIGH
Task status: TODO, IN_PROGRESS, DONE

Interaction examples:
Create task.
--------------------------------
POST http://localhost:8080/api/tasks
Content-Type: application/json

{
  "title": "learn spanish",
  "description": "Read a book",
  "status": "TODO",
  "priority": "HIGH"
}
--------------------------------
Update task.
--------------------------------
PUT http://localhost:8080/api/tasks/1
Content-Type: application/json

{
  "title": "learn english",
  "description": "Read a book",
  "status": "DONE",
  "priority": "HIGH"
}
------------------------------
Delete task: DELETE http://localhost:8080/api/tasks/{task number}
Get task(s): DELETE hGET http://localhost:8080/api/tasks
Get tasks by status: GET http://localhost:8080/api/tasks/status/{TODO}

@github.com/IvanYemtseu
