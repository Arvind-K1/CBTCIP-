# Vite React Projects

This repository contains two Vite React applications: a ToDo List application and a Portfolio application.

## Projects

1. [ToDo List Vite React App](#todo-list-vite-react-app)
2. [Portfolio Vite React App](#portfolio-vite-react-app)

## ToDo List Vite React App

This is a simple ToDo List application built using Vite and React. It allows users to add, edit, delete, and mark tasks as completed. The application also saves the tasks in the local storage so that they persist even after refreshing the page.

### Features

- Add new tasks
- Edit existing tasks
- Delete tasks
- Mark tasks as completed
- Show/Hide completed tasks
- Persist tasks in local storage

### Components

#### Navbar

The `Navbar` component provides navigation links for the application, including links to "Home" and "Your Tasks". It is styled with Tailwind CSS for a responsive design.

#### App

The `App` component is the main component that manages the state and renders the UI for the ToDo list application. It includes functionalities such as:

- Managing the state of the current todo input and the list of todos.
- Adding a new todo.
- Editing an existing todo.
- Deleting a todo.
- Marking a todo as completed.
- Toggling the visibility of completed todos.
- Persisting todos in local storage.

### Getting Started

#### Prerequisites

- Node.js (v12 or later)
- npm or yarn

#### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/vite-react-projects.git
    cd vite-react-projects/todo-app
    ```

2. Install dependencies:
    ```bash
    npm install
    # or
    yarn install
    ```

#### Running the Application

To start the development server, run:
```bash
npm run dev
# or
yarn dev
