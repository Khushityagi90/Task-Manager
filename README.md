# Task Manager Web App

This is a simple and interactive Task Manager built using **JavaScript**, HTML, and CSS for styling. The app allows users to create, edit, delete, and mark tasks as completed—all with live updates in the DOM.

---

## Project Structure

- `index.html` – The main HTML file (not included, but expected to define the necessary UI elements)
- `style.css` – Optional styling file
- `script.js` – JavaScript logic for all task management features

---

## Features

- Add new tasks with a title and description
- Edit existing tasks
- Mark tasks as **complete** or **undo** completion
- Delete tasks
- Live task counter showing total and completed tasks
- Responsive design using Bootstrap classes

---

## How to Use

1. Make sure you have an HTML file that includes:

```html
<form id="task-form">
  <input id="task-title" type="text" placeholder="Task Title" required>
  <textarea id="task-description" placeholder="Task Description" required></textarea>
  <button type="submit">Add Task</button>
</form>

<div id="task-counter"></div>
<ul id="task-list" class="list-group"></ul>

<script src="script.js"></script>
