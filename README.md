# 📝 To-Do List CLI App

A simple and beginner-friendly **To-Do List Command-Line Application built with Python**. This project allows users to add, view, and remove tasks through an interactive terminal menu. It also supports saving tasks to a text file so they remain available after restarting the application.

## 🚀 Features

- ➕ **Add Tasks:** Add new tasks to your to-do list.
- 📋 **View Tasks:** Display all tasks in a numbered, easy-to-read format.
- ❌ **Remove Tasks:** Delete tasks by entering their task number.
- 💾 **File Handling:** Automatically save tasks in a `tasks.txt` file.
- 🔄 **Persistent Storage:** Load previously saved tasks when the application starts.
- 🛡️ **Input Validation:** Handle empty tasks, invalid menu choices, and incorrect task numbers.
- 🧩 **Modular Code:** Use separate functions to organize each feature.

## 🛠️ Technologies Used

- **Language:** Python 3
- **Concepts:** Lists, Functions, Loops, Conditional Statements, Exception Handling, File Handling
- **Interface:** Command-Line Interface (CLI)

## 📂 Project Structure

```text
CodeOrbit_To-Do-List-CLI-App/
│
├── todo.py       # Main Python application
├── tasks.txt     # Automatically created task storage
└── README.md     # Project documentation
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/ksaloni8789/CodeOrbit_To-Do-List-CLI-App.git
```

### 2. Navigate to the Project Folder

```bash
cd CodeOrbit_To-Do-List-CLI-App
```

### 3. Run the Application

Make sure Python 3 is installed on your system.

```bash
python todo.py
```

On some systems, use:

```bash
python3 todo.py
```

## 💻 Usage

After running the program, an interactive menu will appear:

```text
===== TO-DO LIST APP =====
1. Add Task
2. View Tasks
3. Remove Task
4. Exit

Enter your choice:
```

Select an option by entering its corresponding number.

### Example Output

```text
Enter your choice: 1
Enter a new task: Learn Python
Task added successfully!

Enter your choice: 1
Enter a new task: Complete assignment
Task added successfully!

Enter your choice: 2

--- Your To-Do List ---
1. Learn Python
2. Complete assignment
```

## 📚 What I Learned

By building this project, I practiced:

- Creating and using Python functions.
- Managing data with lists.
- Using loops and conditional statements.
- Reading and writing text files.
- Handling invalid user input with `try-except`.
- Organizing a small Python project into reusable components.



## 🤝 Contributing

Suggestions and improvements are welcome! Feel free to fork the repository and submit a pull request.

## 📄 License

This project is open-source and available for educational and personal use.

---

**⭐ If you find this project useful, consider giving the repository a star!**

*Built with ❤️ using Python.*
