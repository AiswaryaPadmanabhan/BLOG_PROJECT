# Django Blog Project

This is a simple Django-based blog application. It allows users to create, edit, and view blog posts. This project also demonstrates basic features of Django, including models, views, templates, and user authentication.

## Features

- User authentication (Login, Registration, Logout)
- Create, Edit, and Delete Blog Posts
- View Blog Posts (with pagination)
- Responsive design (Mobile-friendly)
- User registration and login functionality.
- Users can create, update, and delete their blog posts.
- Each blog post has a title, content, publication date, and an author.
- Views and Templates
- Display a list of all blog posts.
- View individual blog posts.
- Forms for creating blog posts.
- Navigation & Styling
- Easy navigation between pages.
- Basic styling using CSS/Bootstrap.
- 
## Prerequisites

Before running this project, you need to have the following installed:

- Python 3.8+
- Django 3.x+
- pip
- PostgreSQL (or any other database of your choice, see `DATABASES` configuration in `settings.py`)
- 

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/AiswaryaPadmanabhan/BLOG_PROJECT.git

2. 

3. Set up a virtual environment:
   python -m venv env
   source env\bin\activate           #On Windows: venv\Scripts\activate

4. Install dependencies:
   pip install -r requirements.txt

5. Apply database migrations:
   python manage.py makemigrations
   python manage.py migrate

7. Run the application:
   python manage.py runserver

7.Access the application at http://127.0.0.1:8000/
