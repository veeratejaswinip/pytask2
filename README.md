This Python script is a simple command-line To-Do List Manager that allows users to manage their daily tasks. The application uses a list to store 
tasks in memory and a text file (todo.txt)  to persist the data so that the tasks remain saved even after the program ends.
Features:

Add Task:
Users can input new tasks.
The task is appended to the list and saved to todo.txt.

Remove Task:

Displays all tasks with corresponding numbers.
User can remove a task by entering its number.
The list and file are updated after removal.

View Tasks:

Displays all current tasks in a numbered list.
If no tasks are found, it shows an appropriate message.

Persistent Storage:

Tasks are stored in a text file (todo.txt) using Python’s built-in open() function.
When the program starts, it reads the file and loads existing tasks.
On every add/remove operation, the file is updated to reflect the changes.

How It Works:

The load_tasks() function reads tasks from the file and returns them as a list.
The save_tasks() function writes the current list of tasks to the file.
add_task() prompts the user for a task and adds it to the list.
remove_task() deletes a task based on its position in the list.
view_tasks() displays all tasks.
The main() function provides a menu-driven interface using a while loop to repeatedly offer options until the user chooses to exit.
