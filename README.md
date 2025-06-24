# ICC1_todoapp

## Purpose

This repository is meant to be used as a basis for the ICC1 module at Ada.
This is the second task for the part of learning for the capstone project.
Learners will deploy this in a virtual machine on a Cloud Provider such as AWS, Azure, or GCP. 

However, the database aspect has been separated, and is now stored as a managed database instance in the cloud.

A simple Flask-based To-Do application that lets you manage tasks with priorities.

## Features

- Add, view, and delete tasks
- Tasks have priorities (lower number = higher priority)
- Data stored in a local SQLite database

## Getting Started

### Prerequisites

- Python 3.x
- Flask

### Installation

1. Clone this repository:
    ```sh
    git clone <repo-url>
    cd ICC1_todoapp
    ```
2. Install dependencies:
    ```sh
    pip install flask
    ```

### Running the App

**Note:** Running on port 80 may require root privileges.

```sh
sudo python3 app.py
```

## Project Structure

- `app.py` — Main Flask application
- `templates/` — HTML templates

## License

MIT License