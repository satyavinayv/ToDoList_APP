# ToDo List React Component

This React component (`ToDoList`) implements a simple to-do list with the ability to **add tasks**, **delete tasks**, and **reorder tasks**.

## Features

- **Add Task**: Enter a new task in the input field and click **"Add-Task"** to add it to the list.
- **Delete Task**: Click **"Delete-Task"** next to a task to remove it from the list.
- **Move Up**: Click **"MoveUp"** to move a task up in the list (if applicable).
- **Move Down**: Click **"MoveDown"** to move a task down in the list (if applicable).

## Component Structure

The component uses React's `useState` hook to manage state:

- `task`: State array holding the list of tasks.
- `newTask`: State for the input field to add new tasks.

## Functions

- **`handleInputChange`**: Updates `newTask` state as the user types in the input field.
- **`addTask`**: Adds `newTask` to the `task` state array when the user clicks **"Add-Task"**.
- **`deleteTask`**: Removes a task from `task` array based on its index.
- **`moveTaskUp`**: Moves a task up in the list.
- **`moveTaskDown`**: Moves a task down in the list.

## Usage

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/todolist-react.git
    ```
2. **Install dependencies**:
    ```bash
    npm install
    ```
3. **Integrate `ToDoList` component** into your React application:
    ```javascript
    import ToDoList from './ToDoList';

    function App() {
        return (
            <div className="App">
                <ToDoList />
            </div>
        );
    }

    export default App;
    ```
4. **Customize styles and functionalities** as needed.



# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
