# React Todo App

A functional React application for managing todos, built with a focus on interactivity and best practices in state management.

## Features
- **React Context**: Centralized state management for todos.
- **Dynamic UI**: 
  - When there are no todos, the todo creation field is the only visible element.
  - Displays the count of active (not completed) todos.
- **Local Storage**: Automatically saves todos persistently using `localStorage`.
- **Filtering**: Filter todos by status: *All, Active, or Completed*.
- **Todo Management**:
  - Add, delete, or clear completed todos.
  - Toggle individual todo status or mark all as completed.
  - Edit todo titles inline with support for:
    - Enter to save changes.
    - Escape to cancel edits.
    - Deleting the todo if the title is empty.
    - Saving changes on blur.
- **Accessibility**: Interactive elements respond intuitively to user actions, ensuring smooth interactions.

## How to Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/react-todo-app.git

2. Navigate to the project directory:
    ```bash
    cd react-todo-app
3. Install dependencies:
    ```bash
    npm install
4. Start the development server:
    ```bash
    npm start
5. Open http://localhost:3000 in your browser to use the app.

This project implements a fully functional todo management app with modern techniques.

- [DEMO LINK](https://valentyn-radobenko.github.io/todo-app/)
