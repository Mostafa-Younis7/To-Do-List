# To-Do List Web App

A simple and interactive **To-Do List web application** built with **HTML, CSS, and JavaScript**.
It allows users to add tasks, mark them as completed, delete them, and see how many tasks remain.

---

## Features

* ➕ Add new tasks
* ✅ Mark tasks as completed using checkboxes
* 🗑️ Delete tasks from the list
* 🔢 Display the number of remaining tasks
* 🔄 Automatically update the UI when tasks change

---

## How It Works

Tasks are stored in a JavaScript array of objects.

Each task object contains two properties:

```
{
  taskBody: "Task text",
  isFinished: false
}
```

The application dynamically renders tasks in the UI and updates them whenever a task is added, completed, or deleted.

---

## Project Structure

```
project-folder
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## Main Functions

### `displayTasks()`

* Renders all tasks inside the tasks container.
* Creates the HTML elements dynamically.
* Adds event listeners to checkboxes and delete buttons.

### `countTasks()`

* Counts how many tasks are **not finished**.
* Updates the remaining tasks counter in the UI.

### `updateUI()`

* Calls `displayTasks()` and `countTasks()`.
* Shows a message when there are no tasks remaining.

---

## How to Run the Project

1. Clone the repository

```
git clone https://github.com/your-username/your-repository-name.git
```

2. Open the project folder.

3. Open **index.html** in your browser.

---

## Technologies Used

* HTML
* CSS
* JavaScript (DOM Manipulation)

---

## Future Improvements

* Save tasks using **localStorage**
* Add task editing
* Add task filtering (All / Completed / Active)
* Improve UI design

---

## Author

**Mostafa Younis**
Front-End Developer
