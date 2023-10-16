# Project Management Tool

This is a simple project management tool implemented using HTML, CSS, and JavaScript. It allows users to manage projects and tasks associated with those projects. The tool provides functionality to add users, add tasks, change task status, and delete users and tasks.

## Getting Started

To use the project management tool, follow these steps:

1. Download or clone the project files to your local machine.
2. Open the `index.html` file in a web browser.

## Features

### Add User

- Enter a user name in the input field under "New User" section.
- Click the "Add User" button to add the user to the system.

### Delete User

- Select a user from the dropdown list under "Delete User" section.
- Click the "Delete User" button to remove the selected user from the system. This action will also delete all tasks associated with the user.

### Add Task

- Click the "Add Task" button to open a modal dialog.
- In the modal dialog, select a user from the dropdown list.
- Enter a task description in the input field.
- Click the "Add Task" button in the modal dialog to add the task to the selected user.

### Change Task Status

- For each task in the table, there is a "Change Status" dropdown list.
- Select a status option from the dropdown list to update the task status.
- Available options are:
  - Start: Start the task timer.
  - Stop: Stop the task timer.
  - Progress: Change the task status to "Progress."
  - Complete: Mark the task as completed.
  - Delete: Delete the task from the system.

### Task Table

- The table displays all tasks for each user.
- The table columns include:
  - Task: The description of the task.
  - User Name: The name of the user associated with the task.
  - Task Status: The current status of the task.
  - Duration: The duration of the task (displayed as hours:minutes:seconds).
  - Date: The date when the task was started.
  - Change Status: Dropdown list to change the task status.

## Styling

The project management tool uses a custom CSS file (`style.css`) and the Bootstrap library for styling. The tool has a responsive design and a gradient background color.

## Scripts

The functionality of the project management tool is implemented using JavaScript in the `script.js` file. The script handles actions such as adding users, adding tasks, changing task status, and deleting users and tasks. It also includes functions to load projects and tasks from local storage and update the task table dynamically.

## External Dependencies

The project management tool relies on the following external dependencies:

- [jQuery](https://jquery.com/): JavaScript library for DOM manipulation.
- [Bootstrap](https://getbootstrap.com/): CSS framework for responsive design and UI components.
- [SweetAlert](https://sweetalert.js.org/): JavaScript library for beautiful alert dialogs.

These dependencies are loaded from CDNs in the HTML file.

## Author

This project was created by [Veeramanikandan].
