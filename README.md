ToDo List React Component
This repository contains a React component called ToDoList, which implements a basic to-do list application. The component allows users to add tasks, delete tasks, and rearrange the order of tasks in the list.

Features
Add Task: Enter a new task in the input field and click "Add-Task" to add it to the list.
Delete Task: Click "Delete-Task" next to a task to remove it from the list.
Move Up: Click "MoveUp" to move a task up in the list (if applicable).
Move Down: Click "MoveDown" to move a task down in the list (if applicable).

Component Structure
The component uses React's useState hook to manage state:
task: State array holding the list of tasks.
newTask: State for the input field to add new tasks.

Functions
handleInputChange: Updates newTask state as the user types in the input field.
addTask: Adds newTask to the task state array when the user clicks "Add-Task".
deleteTask: Removes a task from task array based on its index.
moveTaskUp: Moves a task up in the list.
moveTaskDown: Moves a task down in the list.

Usage
Clone the repository.
Install dependencies (react and react-dom).
Integrate ToDoList component into your React application.
Customize styles and functionalities as needed.


# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
