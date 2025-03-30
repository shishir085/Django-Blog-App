# Django Blog Application

This is a beginner-friendly blog application built with Django. It allows users to create, edit, and delete blog posts, manage user profiles, and interact with other users through comments.

## Features

- User authentication (sign up, log in, log out, password reset, and change password)
- User profile management (edit profile, upload profile picture)
- Create, update, and delete blog posts
- Add tags to posts
- Comment on blog posts
- Pagination for blog posts
- Responsive design using Bootstrap



## Installation

1. Clone the repository:

```bash
git clone https://github.com/shishir085/Django-Blog-App
cd django-blog-app
```

2. Create and activate a virtual environment:
```bash
python -m venv venv

## On Windows: 
venv\Scripts\activate

## On Mac: 
source venv/bin/activate  
```


3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up the database:
```bash
python manage.py makemigrations
python manage.py migrate
```
5. Create a superuser:
```bash
python manage.py createsuperuser
```
6. Run the development server:
```bash
python manage.py runserver
```
7. Open your browser and navigate to http://127.0.0.1:8000.