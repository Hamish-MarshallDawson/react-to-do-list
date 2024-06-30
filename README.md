# To-Do List Application

## Project Description

This is a simple To-Do List application built with React.js. The application allows users to add, delete, and reorder tasks. Users can input new tasks, move tasks up or down in the list, and remove tasks when they are completed.

## Features

- Add new tasks to the list
- Delete tasks from the list
- Move tasks up and down in the list
- Input validation to prevent empty tasks

## Technologies Used

- React.js
- CSS

## Getting Started

### Prerequisites

Ensure you have the following software installed on your local development machine:

- Node.js (https://nodejs.org/)

### Installation

1. Clone the repository to your local machine:

   ```sh
   git clone https://github.com/your-username/todo-list-react.git
   ```

2. Navigate to the project directory:

   ```sh
   cd todo-list-react
   ```

3. Install the dependencies:

   ```sh
   npm install
   ```

### Running the Application

1. Start the development server:

   ```sh
   npm start
   ```

2. Open your web browser and navigate to `http://localhost:3000` to use the To-Do List application.

## Project Structure

```
todo-list-react/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── Components/
│   │   ├── ToDoList.js
│   │   └── ...
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   └── ...
├── package.json
├── README.md
└── ...
```

- `public/`: Contains the HTML file and other public assets.
- `src/`: Contains the React components, CSS, and JavaScript files.
  - `Components/`: Contains the individual component files (`ToDoList.js`, etc.).
  - `App.js`: Main React component that initializes the app.
  - `App.css`: Styles for the application.
  - `index.js`: Entry point for the React application.

## To-Do List Logic

### Main Component

- `ToDoList.js`: The main component that handles the to-do list logic and state.

### State Management

- `tasks`: An array that stores the list of tasks.
- `newTask`: A string that stores the current input value for a new task.

### Functions

- `handleInputChange(event)`: Updates the `newTask` state with the value from the input field.
- `addTask()`: Adds a new task to the `tasks` array if the input is not empty.
- `deleteTask(index)`: Removes a task from the `tasks` array based on its index.
- `moveTaskUp(index)`: Moves a task up in the list.
- `moveTaskDown(index)`: Moves a task down in the list.

## Styling

The CSS styles are defined in `App.css` to provide a simple and clean layout for the To-Do List application.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. Contributions and improvements are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Enjoy managing your tasks with the To-Do List application! If you have any questions or feedback, feel free to open an issue in the repository.
