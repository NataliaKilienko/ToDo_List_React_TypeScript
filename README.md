# To-Do List Application

A feature-rich To-Do List application built with React and TypeScript, implementing full **CRUD** (Create, Read, Update, Delete) functionality. This app allows users to manage their tasks effectively by providing features such as adding, editing, deleting, searching, sorting, and filtering tasks. Each task can also be marked as completed or require confirmation before editing.

## Features

1. **Add Task**: Users can add a new task with a title and description.
2. **Delete Task**: Users can delete tasks from the list.
3. **Edit Task**: Users can edit existing tasks. Tasks that require confirmation prompt the user before editing.
4. **Mark as Completed**: Tasks can be marked as completed.
5. **Task Types**: Supports two types of tasks - default tasks and tasks that require confirmation before editing.
6. **Search Functionality**: Allows users to search tasks by name or content.
7. **Sorting**: Tasks can be sorted by status (completed or incomplete) or by creation date.
8. **Responsive Design**: The application is fully responsive and adapts to different screen sizes, providing an optimal user experience on desktop, tablet, and mobile devices.

## Technologies Used

- **React**: Frontend library for building user interfaces.
- **TypeScript**: For type-checking and enhancing JavaScript.
- **uuid**: To generate unique IDs for tasks.

## Components

- **TaskInput**: For adding new tasks, including an option to mark tasks as requiring confirmation.
- **TaskItem**: Displays individual tasks with options to edit, delete, and mark as complete.
- **SearchBar**: For searching and sorting tasks.
- **TaskStatistics**: Displays statistics on the total tasks and incomplete tasks.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/NataliaKilienko/ToDo_List_React_TypeScript.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Todo_List
    ```
3. Install dependencies:
    ```bash
    npm install
    ```
4. Start the development server:
    ```bash
    npm start
    ```

## Folder Structure

- `src/components`: Contains reusable components like `TaskInput`, `TaskItem`, `SearchBar`, etc.
- `src/types`: Contains TypeScript interfaces and types for the project.
- `src/services`: Contains utility functions for handling task operations like filtering, sorting, and managing task states.
- `src/assets`: Stores any static assets such as images or backgrounds used in the application.

## How to Use

- **Add a New Task**: Enter the task title in the input box, check "Requires Confirmation" if needed, and click "Add Task".
- **Edit a Task**: Click the "Edit" button next to the task, modify the text, and click "Save". If the task requires confirmation, a prompt will appear.
- **Delete a Task**: Click the "X" button next to the task to remove it.
- **Search and Sort**: Use the search bar to filter tasks by name or content, and sort them by date or status.

## Additional Details

- **Responsive Styling**: The application adjusts its layout and element sizing for better usability on various screen sizes, from desktop to mobile.
- **Input Validation**: Both the title and content fields are required for adding and editing tasks to ensure meaningful entries.
- **Enums for Sorting**: Sorting criteria are implemented using TypeScript enums for clarity and type safety.
- **Task Status**: Task items can be toggled between completed and uncompleted states, and the status is reflected in the sorting options.