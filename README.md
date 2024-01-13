
# Todoos Django Project

A simple Django project for managing todos with a RESTful API.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Todoos Django project is a straightforward application for managing todos. It comes with a Django backend that provides a RESTful API for interacting with todo items.

## Features

- Create, read, update, and delete todos through a RESTful API.
- Django Admin interface for easy management.
- User authentication for securing todo data.
- Customizable and extendable for additional features.

## Requirements

Make sure you have the following requirements installed on your system:

- Python 3.x
- Django
- Django Rest Framework

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Yashnarbek-Samiyev/todoos-djangoapi.git
   cd todoos-django
   ```

2. Create a virtual environment (optional but recommended):

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run migrations:

   ```bash
   python manage.py migrate
   ```

5. Create a superuser for Django Admin:

   ```bash
   python manage.py createsuperuser
   ```

6. Run the development server:

   ```bash
   python manage.py runserver
   ```

## Usage

Visit the Django Admin interface at `http://localhost:8000/admin/` to manage todos using the provided API.

## API Endpoints

- List all todos: `/api/todos/` (GET)
- Create a new todo: `/api/todos/` (POST)
- Retrieve a specific todo: `/api/todos/{id}/` (GET)
- Update a specific todo: `/api/todos/{id}/` (PUT, PATCH)
- Delete a specific todo: `/api/todos/{id}/` (DELETE)

Make sure to include the necessary authentication headers in your API requests.

## Contributing

If you would like to contribute to this project, please follow the guidelines in [CONTRIBUTING.md](CONTRIBUTING.md).

## License

This project is licensed under the [UIC group License](LICENSE).
