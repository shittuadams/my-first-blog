# Skalearn Blog - Django Blog Project

Welcome to the **Skalearn Blog** project! This blog is a simple web application built with **Django**, a powerful web framework for Python. The project allows you to create, view, and manage blog posts with various features, including pagination and styling for a clean user interface.

## Table of Contents
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Features](#features)
- [License](#license)

## Technologies Used
- **Python**: Backend logic and server-side development
- **Django**: Web framework used for building the blog
- **HTML/CSS**: Structure and styling of the blog
- **Bootstrap**: For responsive design and quick styling
- **SQLite**: Default database for development (can be swapped for others)

## Setup Instructions

### Prerequisites
- Install [Python](https://www.python.org/downloads/)
- Install [pip](https://pip.pypa.io/en/stable/) (Python package manager)
- Install [virtualenv](https://virtualenv.pypa.io/en/latest/)

### Installation Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/my-first-blog.git
    ```

2. Navigate into the project directory:
    ```bash
    cd my-first-blog
    ```

3. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    ```

4. Activate the virtual environment:
    - On macOS/Linux:
        ```bash
        source venv/bin/activate
        ```
    - On Windows:
        ```bash
        .\venv\Scripts\activate
        ```

5. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

6. Run migrations to set up the database:
    ```bash
    python manage.py migrate
    ```

7. Create a superuser for accessing the admin panel:
    ```bash
    python manage.py createsuperuser
    ```

8. Start the development server:
    ```bash
    python manage.py runserver
    ```

9. Access the blog at `http://127.0.0.1:8000/` and the admin panel at `http://127.0.0.1:8000/admin/`.

## Usage
- To create a new blog post, visit the admin panel and log in using the superuser credentials.
- You can view and manage posts on the blog's homepage, edit existing posts, and create new ones.

## Features
- **Create new posts**: Add new blog posts with a title and body content.
- **View posts**: View blog posts with automatic pagination.
- **Edit posts**: Edit existing blog posts from the admin panel.
- **Responsive design**: The blog is mobile-friendly and adjusts to various screen sizes using Bootstrap.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

