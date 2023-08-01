# django-todo-app

This is a simple web app that lets you manage your tasks using Django and SQLite.
You can create, update, delete, and mark as completed your tasks.
You can also use the API to perform CRUD operations on the tasks, with authentication, pagination, filtering, and searching features.

## Installation

- Clone this repo: `git clone https://github.com/Erfan-1379/django-todo-app.git`
- Go to the project folder: `cd django-todo-app`
- Create and activate a virtual environment: `python -m venv venv` and `source venv/bin/activate`
- Install the dependencies: `pip install -r requirements.txt`
- Apply the migrations: `python manage.py migrate`
- Create a superuser: `python manage.py createsuperuser`
- Run the server: `python manage.py runserver`

## Usage

- Go to http://localhost:8000/admin/ to access the admin panel
- Go to http://localhost:8000/api/todos/ to view the list of tasks
- Go to http://localhost:8000/api/todos/<id>/ to view, edit, or delete a specific task
- Use tools like Postman or curl to interact with the API

## Contact

Email me at yaghoblo41@gmail.com
