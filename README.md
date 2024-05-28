# Employee Management System

A simple Employee Management System built with Django for managing employee records.

## Features

- Add, view, update, and delete employee records.

## Installation

1. **Clone the repository:**

    ```sh
    git clone <repository_url>
    cd employee_project
    ```

2. **Set up virtual environment:**

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies:**

    ```sh
    pip install django
    ```

4. **Run migrations:**

    ```sh
    python manage.py makemigrations
    python manage.py migrate
    ```

5. **Create a superuser:**

    ```sh
    python manage.py createsuperuser
    ```

6. **Start the server:**

    ```sh
    python manage.py runserver
    ```

7. **Access admin interface:**

    Go to `http://127.0.0.1:8000/admin` and log in with the superuser account.

## License

Licensed under the MIT License.
