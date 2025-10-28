# System Architecture

The **To-Do List Manager** system follows a simple client-server architecture.

## Components

1. **Frontend (HTML/CSS/JavaScript)**
   - Displays the task list.
   - Allows users to add, edit, and delete tasks via forms.

2. **Backend (Flask - Python)**
   - Handles requests like:
     - `GET /tasks` – List all tasks
     - `POST /tasks` – Add a new task
     - `PUT /tasks/<id>` – Update a task
     - `DELETE /tasks/<id>` – Delete a task

3. **Database (SQLite)**
   - Stores all tasks with:
     - `id`, `title`, `description`, `due_date`, `completed`

---

## Diagram (simple text version)

```
[ User Interface ]
     ↓
[ Flask Backend ]
     ↓
[ SQLite Database ]
```
