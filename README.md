# Todo App 📝

A responsive and minimal todo app built with **React + TypeScript**. Easily manage your daily tasks with features like editing, filtering, and persistent storage using `localStorage`.

## 🔗 Live Demo

👉 [Try the app](https://kovalmaria.github.io/todo-app/)

## ✨ Features

- ➕ **Add, edit, and delete tasks** — Full control over your todo list
- 📦 **Saved in localStorage** — Tasks persist after page reload
- ✅ **Mark tasks as completed** — Organize your finished work
- 🔎 **Filter by status** — View All, Active, or Completed tasks
- 🧠 **Context API** — Global state management with React Context
- ⚙️ **Custom hook (`useLocalStorage`)** — Encapsulated logic for storage
- 📱 **Responsive layout** — Looks great on all devices
- 🎨 **SCSS styling** — Modular and maintainable styles
- 🧼 **Clean & intuitive UI** — Simple design for better UX

## 🛠 Technologies Used

- **React** with **TypeScript**
- **React Context API**
- **Custom Hooks**
- **SCSS (Modular structure)**:
  - `todoapp.scss`
  - `todo-list.scss`
  - `filters.scss`
- **localStorage API**
- **Vite** — Fast development server

## 📁 Folder Structure

src/
├── Components/
│ ├── Footer.tsx
│ ├── Header.tsx
│ ├── TodoItem.tsx
│ └── TodoList.tsx
├── Hooks/
│ └── useLocalStorage.ts
├── styles/
│ ├── filters.scss
│ ├── index.scss
│ ├── todo-list.scss
│ └── todoapp.scss
├── TodoContext/
│ └── TodoContext.tsx
├── types/
│ └── Todo.ts
├── App.tsx
└── index.tsx