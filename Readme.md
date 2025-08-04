# Blog API

This project is a RESTful API for a blog application built with Django and Django REST Framework.

## Features

- User authentication (registration, login)
- CRUD operations for blog posts
- Commenting system
- API endpoints for posts, comments, and users

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/kaleb-mulugeta/blogapi.git
    cd blogapi
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Apply migrations:
    ```bash
    python manage.py migrate
    ```
4. Run the development server:
    ```bash
    python manage.py runserver
    ```

## Usage

Access the API at `http://localhost:8000/api/`.

## Technologies

- Django
- Django REST Framework

## License

This project is licensed under the MIT License.