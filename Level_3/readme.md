# 📝 Task Management System – Python

## 📌 Project Overview

The Task Management System is a menu-driven Python application developed as part of my Software Development Internship at Cognifyz Technologies.

It allows users to create, view, update, and delete tasks. The application stores task data in a text file (`tasks.txt`), so the data can be loaded again when the program is restarted.

## ✨ Features

* **Create Tasks:** Add new tasks with a title and description.
* **View Tasks:** Display all saved tasks with their IDs.
* **Update Tasks:** Modify existing task details.
* **Delete Tasks:** Remove tasks using their unique IDs.
* **File Handling:** Save and load task data using `tasks.txt`.
* **Input Validation:** Handle invalid IDs, empty titles, and incorrect menu choices.
* **Exception Handling:** Handle file errors and invalid numeric inputs.
* **Automatic Task IDs:** Assign unique sequential IDs to new tasks.

## 🛠️ Technologies Used

* **Programming Language:** Python
* **IDE:** Visual Studio Code
* **Modules:** `os`
* **Storage:** Text File (`tasks.txt`)

## 🔄 CRUD Operations

This project implements all four CRUD operations:

| Operation | Function        | Description              |
| --------- | --------------- | ------------------------ |
| Create    | `create_task()` | Adds a new task          |
| Read      | `read_tasks()`  | Displays all tasks       |
| Update    | `update_task()` | Updates an existing task |
| Delete    | `delete_task()` | Deletes a task           |

## 📂 Project Structure

```text
Task-Management-System/
│
├── task_management.py
├── tasks.txt
└── README.md
```

**Note:** The `tasks.txt` file is created automatically when tasks are saved. It does not need to exist before the first run.

## ▶️ How to Run

1. Install Python on your computer.
2. Clone or download this project repository.
3. Open the project folder in Visual Studio Code.
4. Open the terminal in the project directory.
5. Run the following command:

```bash
python task_management.py
```

Replace `task_management.py` with your actual Python filename if it is different.

## 💻 Sample Output

```text
Task data loaded from file.

===== TASK MANAGEMENT SYSTEM =====
1. Create Task
2. View Tasks
3. Update Task
4. Delete Task
5. Exit

Enter your choice (1-5): 1
Enter task title: Complete Python Project
Enter task description: Finish the internship task

Task created and saved successfully!
Task ID: 1
```

## 🧠 Python Concepts Used

* Classes and Objects
* Functions
* Lists
* Conditional Statements (`if-elif-else`)
* Loops (`for`, `while`)
* File Handling (`open`, `read`, `write`)
* Exception Handling (`try-except`)
* Global Variables
* Input Validation
* The `os` Module

## 🎯 Learning Outcomes

Through this project, I gained practical experience in implementing CRUD operations, organizing code using functions and classes, managing data with file handling, and handling invalid user inputs and file-related errors.

## 👨‍💻 Internship Details

* **Organization:** Cognifyz Technologies
* **Domain:** Software Development
* **Project:** Task Management System
* **Task:** Level 2 – Task 3
* **Programming Language:** Python
* **Status:** Completed ✅

---

⭐ Thank you for visiting my project repository!
