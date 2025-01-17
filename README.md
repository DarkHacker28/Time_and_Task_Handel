
# Todo App

A simple Todo app built using Node.js, npm, and JavaScript. This app allows users to add, update, and delete tasks. It also allows the user to mark tasks as completed and provides a persistent storage solution for managing tasks.

## Features

- Add new tasks
- Mark tasks as completed
- Edit existing tasks
- Delete tasks
- Persistent storage of tasks
- Responsive user interface

## Technologies Used

- **Node.js**: JavaScript runtime environment for server-side scripting.
- **npm**: Node.js package manager to manage libraries and dependencies.
- **JavaScript**: For client-side and server-side scripting.
- **Express**: Web framework for building the server and routing.
- **MongoDB** (Optional): NoSQL database for persistent task storage.
- **EJS** (or another templating engine): For rendering dynamic HTML pages.
- **CSS/HTML**: For styling and structuring the front-end.

## Installation

Follow these steps to set up the project locally:

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/todo-app.git
```

### 2. Install dependencies
Navigate to the project folder and install the required npm packages:
```bash
cd todo-app
npm install
```

### 3. Set up the environment
You may need to configure environment variables for MongoDB (or another database). If using MongoDB locally, ensure it is running and set the connection string in the `.env` file.

### 4. Run the application
Once the dependencies are installed, start the application:
```bash
npm start
```
This will start the server, and you can view the app at `http://localhost:3000`.

## Usage

- Visit the app in your browser to see the Todo list.
- Add new tasks by typing in the input box and clicking "Add".
- Mark tasks as completed by clicking the checkbox next to each task.
- Edit tasks by clicking on them.
- Delete tasks by clicking the delete icon next to each task.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

