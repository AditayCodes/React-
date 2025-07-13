
# 📝 React Todo App (Context API)
A minimal Todo application built with React, utilizing the Context API for state management. Learn how to manage global state (todos) without third-party libraries!

## 🧩 Features
- Add, toggle, and delete todos
- Centralized state via Context API
- Reusable components with clear separation of concerns
- Built with functional components and React Hooks

## 🚀 Getting Started

### Prerequisites
- Node.js (v14+) and npm

### Setup
1. **Clone the repo:**
```
git clone https://github.com/AditayCodes/React-.git
cd React-/05todoContext
```

2. **Install dependencies:**
   ```
   npm install
   ```
   
3. **Run the development server:**
   ```
   npm start
   ```

## 🧱 Project Structure
```
05todoContext/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── TodoInput.jsx
│   │   ├── TodoList.jsx
│   │   └── TodoItem.jsx
│   ├── context/
│   │   └── TodoContext.jsx
│   ├── App.jsx
│   └── index.jsx
└── package.json
```

## 📚 Context API Overview
- **todos** — current todo items array
- **addTodo(text)** — add a new todo
- **toggleTodo(id)** — toggle completed state
- **deleteTodo(id)** — remove a todo

## 📄 License
MIT License — feel free to use and modify this code.

