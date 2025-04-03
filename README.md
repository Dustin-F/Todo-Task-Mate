# 📝 Task Mate

**Task Mate** is a lightweight React-based To-Do List app with theme support, task editing, and local storage persistence. Designed to be clean, responsive, and functional — without bloated frameworks or unnecessary libraries.

## 🚀 Features

- ✅ Add, edit, and delete tasks  
- 🕒 Each task is timestamped automatically  
- 💾 LocalStorage persistence (your tasks survive page refreshes)  
- 🎨 Dynamic theme selector with 6 themes  
- 🧹 "Clear All" functionality  
- 📱 Responsive design

## 📸 Preview

**COMING SOON**

## 🧠 Tech Stack

- React (Functional Components + Hooks)
- Vanilla CSS for styling
- Bootstrap Icons for edit/delete buttons
- LocalStorage for data persistence



## ⚙️ How It Works

### App State
- `tasklist`: An array of task objects (`{ id, name, time }`) stored in localStorage.
- `task`: A temporary state object used when adding/editing tasks.

### AddTask.jsx
- Handles both adding a new task and editing an existing one.
- If a task has an `id`, it's updated; otherwise, a new one is created using `Date.getTime()`.

### ShowTask.jsx
- Displays tasks with the option to edit or delete.
- Editing populates the input with the selected task.
- "Clear All" wipes out the full task list.

### Header.jsx
- Contains the logo and theme selector.
- Selected theme is stored in localStorage and applied to `document.documentElement`.

### Themes
Themes change the background via custom CSS classes. You can choose from:
- `light`
- `medium`
- `dark`
- `gOne`
- `gTwo`
- `gThree`

## 🛠 How to Use
git clone https://github.com/yourusername/task-mate.git
cd task-mate
npm install
npm start
### Clone and run locally

```bash
git clone https://github.com/yourusername/task-mate.git
cd task-mate
npm install
npm start

“It’s a to-do app. You’ve seen a million. This one’s mine. It has themes. That’s it. Move along.”
