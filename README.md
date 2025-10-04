# ✅ To-Do List App

A sleek **To-Do List application** built with **HTML, CSS, TailwindCSS, and Vanilla JavaScript**.  
This app allows you to add, complete, delete, and save tasks with due dates. Tasks persist using **LocalStorage**.

---

## 🚀 Features
- 📝 **Add Tasks** – Enter a task with a due date.
- ✅ **Mark as Completed** – Toggle tasks as done/undone with a checkbox.
- 🗑️ **Delete Tasks** – Remove unwanted tasks.
- 💾 **Persistent Storage** – Tasks are saved in `localStorage` so they remain after page reload.
- 🎨 **TailwindCSS Styling** – Clean and responsive UI.
- ⌨️ **Keyboard Support** – Press **Enter** to quickly add a task.

---

## 🛠️ Tech Stack
- **HTML5**
- **CSS3 + TailwindCSS**
- **Vanilla JavaScript (ES6+)**
- **LocalStorage API**

---


---

## 🖥️ Setup & Usage

### 1. Clone or Download the Project
```bash
git clone https://github.com/yourusername/todo-app.git
cd todo-app
<div class="max-w-lg mx-auto mt-10 space-y-4">
  <h1 class="text-3xl font-bold text-center">To-Do List</h1>

  <div class="flex gap-2">
    <input type="text" class="todo_input border p-2 rounded flex-grow" placeholder="Add a task...">
    <input type="date" class="todo_date border p-2 rounded">
    <button class="todo_button bg-indigo-600 text-white px-4 py-2 rounded hover:bg-indigo-700">Add</button>
  </div>

  <ul class="todo_list space-y-2"></ul>
</div>

<script src="script.js"></script>
<link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
