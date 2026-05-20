# Task Tracker CLI

Command-line task manager developed in Python for task organization and workflow management.

## Features

- Add tasks
- Update tasks
- Delete tasks
- Change task status
- List tasks
- Filter tasks by status
- JSON data persistence
- Command-line argument support
- Interactive terminal menu

## Technologies

- Python
- JSON
- Datetime
- Sys.argv

## Project Structure

Each task contains:

```json
{
  "taskID": 1,
  "description": "Study FastAPI",
  "status": "in-progress",
  "createdAt": "14/01/2026 15:30",
  "updateAt": "14/01/2026 16:00"
}
