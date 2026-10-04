# Django Setup & Project Fundamentals

## Python Installation

> **python --version**

> **py --version**

> **python -m pip --version**

> **py -m pip --version** 

## Virtual Environments

**A virtual environment is an isolated Python environment for a particular project. Installing everything globally can create dependency conflicts. A virtual environment keeps each project's packages separate.**

- Without virtual environment :: Packages from different projects can interfere with each other.

```py
Computer
 └── Python
      ├── Django
      ├── NumPy
      ├── Flask
      └── Other packages
```

- With virtual environments
```py
Computer
│
├── Project A
│    └── venv
│         └── Django
│
└── Project B
     └── venv
          └── Different Django version
```

## Create a virtual environment

```py
mkdir django_app
cd django_app

# Create the virtual environment
python -m venv venv

# or You can name it anything

python -m venv myenv

# Activate the environment on Windows
venv\Scripts\activate
```

## Setup Django App

```py
pip install django
# or
python -m pip install django

# Upgrade pip
python -m pip install --upgrade pip

# See installed packages
pip list

# Save dependencies
pip freeze

# 
pip freeze > requirements.txt

# Verify
django-admin --version
# or
python -m django --version

# Recommended verification
python -m django --version

```

## Creating a Django Project

```py
django-admin startproject myproject

# Better development structure
django-admin startproject myproject .
```
> The . means: Create the project in the current directory rather than creating another outer folder.

```
django_app/
│
├── venv/
│
├── manage.py
│
└── myproject/
    ├── __init__.py
    ├── settings.py
    ├── urls.py
    ├── asgi.py
    └── wsgi.py
```


```py
python manage.py startapp products

python manage.py runserver
```

