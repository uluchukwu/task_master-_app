# Task Master

Task Master is a basic CRUD (Create, Read, Update, Delete) application built with Flask and SQLAlchemy. It allows users to manage a list of tasks, with functionalities to add, view, update, and delete tasks.

## Features

- **Create**: Add new tasks to the task list.
- **Read**: View all tasks in the task list.
- **Update**: Edit the content of an existing task.
- **Delete**: Remove a task from the task list.

## Technologies Used

- **Flask**: A lightweight WSGI web application framework.
- **SQLAlchemy**: An SQL toolkit and Object-Relational Mapping (ORM) library for Python.
- **SQLite**: A C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine.
- **HTML/CSS**: For structuring and styling the web pages.

## Getting Started

### Prerequisites

- Python 3.x
- Flask
- Flask-SQLAlchemy

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/uluchukwu/task_master-_app
    cd task-master
    ```

2. Create and activate a virtual environment:

    ```bash
    python -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```

3. Install the required packages:

    ```bash
    pip install flask flask_sqlalchemy
    ```

4. Initialize the database:

    ```bash
    python init_db.py
    ```

5. Run the application:

    ```bash
    python app.py
    ```

6. Open your browser and navigate to `http://127.0.0.1:5000/` to use the Task Master application.

## File Structure

- `app.py`: The main application file containing the Flask routes and models.
- `init_db.py`: Script to initialize the database.
- `templates/`: Directory containing HTML templates.
  - `index.html`: Template for the main task list page.
  - `update.html`: Template for the update task page.
- `test.db`: SQLite database file.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
