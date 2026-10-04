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








```py
mkdir django_app

cd django_app

python -m venv venv

venv\Scripts\activate

python -m pip install django

django-admin startproject ecommerce .

python manage.py startapp products

python manage.py runserver
```

```py
Install Python
     ↓
Create Virtual Environment
     ↓
Activate Environment
     ↓
Install Django using pip
     ↓
Create Django Project
     ↓
Create Django Application
     ↓
Configure settings.py
     ↓
Configure urls.py
     ↓
Run Development Server
```
