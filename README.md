## Flask Python Crash Course

A hands-on learning repository featuring personal solutions and experiments using Flask, Python and SQLite, for educational purposes. It demonstrates a RESTful API for managing CRUD operations.

### Features

- View all tasks
- Add new tasks
- Update existing tasks
- Delete tasks
- Simple client's UI and tasks storage using SQLite database

### Getting Started

#### Prerequisites

- [Python 3.8+](https://www.python.org/downloads/)

#### Create and activate a virtual environment

- Run `pip3 install virtualenv` to install the virtual environment
- Use `virtualenv env` to create the virtual environment
- To access the virtual environment use `source env/bin/activate`

#### Dependencies installation

- Install the dependencies `pip3 install flask flask-sqlalchemy`

#### Accessing the Flask application

- Run `python3 app.py`. The application is available at `http://127.0.0.1:5000`

### API Endpoints

| Method   | Route              | Description            |
| -------- | ------------------ | ---------------------- |
| GET      | `/`                | List all tasks         |
| POST     | `/`                | Add a new task         |
| GET      | `/delete/<int:id>` | Delete a specific task |
| GET/POST | `/update/<int:id>` | Edit an existing task  |

### LICENSE

This project is licensed under the MIT License.

### Todo

- Add tests and openapi/swagger
