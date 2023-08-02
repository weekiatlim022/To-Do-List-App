![To-Do-List-App Screenshot](/public/screenshot.png)
# To-Do List App in ReactJS

This is a simple To-Do List app built using ReactJS. The app allows users to add, edit, and delete tasks, as well as mark tasks as completed. It provides a straightforward and user-friendly interface for managing tasks efficiently.
**Live demo**: https://weekiatlim022.github.io/To-Do-List-App/

## Components

### App.js

The main entry point of the application. It renders the `TodoWrapper` component.

### TodoWrapper.js

This component is the core of the To-Do List app. It manages the state of tasks and handles their creation, modification, and deletion. The `TodoWrapper` component includes the following functionality:

- **Add Task**: Users can add new tasks to the list using the `TodoForm`.

- **Toggle Completion**: By clicking on a task, users can mark it as completed or incomplete.

- **Edit Task**: Users can edit a task by clicking on the edit icon, which triggers the `EditTodoForm` component.

- **Delete Task**: Tasks can be deleted by clicking on the delete icon.

### TodoForm.js

A form component that allows users to input new tasks and add them to the list.

### Todo.js

This component represents an individual task in the To-Do List. It displays the task's name and provides options to mark it as completed, edit the task, or delete it.

### EditTodoForm.js

A form component that enables users to edit the name of a task and update it in the list.

## How to Use

1. **Adding a Task**: To add a new task, simply type the task's name in the input field of the `TodoForm` and press Enter or click the "Add" button.

2. **Marking a Task as Completed**: Click on an incomplete task to mark it as completed. Click again to mark it as incomplete.

3. **Editing a Task**: Click on the pen icon next to a task to activate edit mode. This will open the `EditTodoForm` with the current task's name pre-filled. Update the task name and press Enter or click the "Update Task" button to save the changes.

4. **Deleting a Task**: Click on the trash icon next to a task to delete it from the list.

## Getting Started

To run the To-Do List app locally, follow these steps:

1. Clone the repository.

2. Install the required dependencies using `npm install`.

3. Run the app using `npm start`.

## Dependencies

The app uses the following external libraries:

- `uuid`: A library for generating unique identifiers.

- `@fortawesome/react-fontawesome` and `@fortawesome/free-solid-svg-icons`: Libraries for using Font Awesome icons.

