# To-Do List CLI
A simple command-line interface (CLI) application for managing a to-do list, written in Python. It allows you to add, list, toggle, and delete tasks. All tasks are stored in a local `tasks.json` file.
## Requirements
- Python 3.6 or newer
## Usage
- Add a task -> python todo.py add "Task description"
- List all tasks -> python todo.py list
- Toggle a task's status (done/undone) -> python todo.py toggle <task_number>
- Delete a task -> python todo.py delete <task_number>
## Example
$ python todo.py add "Write a README file"
Task added: Write a README file

$ python todo.py list
1. [ ] Write a README file

$ python todo.py toggle 1
Task 1 toggled.

$ python todo.py list
1. [x] Write a README file
