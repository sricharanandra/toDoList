# Simple To-Do List App

This is a simple to-do list application built using HTML, CSS, and JavaScript. It allows users to add tasks, mark them as completed, and delete them. Tasks are saved locally using browser storage.

## Features

- Add new tasks.
- Mark tasks as completed.
- Delete tasks.
- Data persists in browser storage.

## Usage

1. Clone the repository:

   ```bash
   git clone <repository_url>
2. Open `index.html` in your web browser.

3. Start adding tasks to your to-do list.

## Code Overview

### HTML Structure

The HTML structure includes a form for adding new tasks and an unordered list (`ul`) to display the tasks.

### JavaScript Logic

- **Adding a Task**: When the form is submitted, the `addTodo()` function is called to create a new list item (`<li>`) with the task text. This function also updates local storage.
  
- **Marking a Task as Completed**: Clicking on a task toggles its completed status. The `updateLS()` function is called to update local storage.
  
- **Deleting a Task**: Right-clicking on a task removes it from the list. The `updateLS()` function is called to update local storage.

### Local Storage

Tasks are stored locally in the browser's storage using JSON format. This allows tasks to persist even after the page is refreshed or closed.
