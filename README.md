# Django : A Python Web Framework

**Django is a high-level, open-source web framework written in Python. It helps developers build secure, scalable, and maintainable web applications quickly by providing built-in components for common web development tasks.**

**Django follows the MTV (Model–Template–View) architectural pattern and includes features such as an ORM, authentication, URL routing, an administrative interface, and form handling.**

## Why do we use Django?

- Employee registration and login
- Employee records stored in a database
- Forms to add and update employee information
- HTML pages to display employee details
- Authentication and authorization
- Administrative access to manage records

## Feature	Explanation	Example

ORM :	Interacts with databases using Python objects	Employee.objects.all()
Authentication :	Handles users, passwords, and login	User login system
Admin panel :	Provides a built-in administrative interface	Manage employees
URL routing :	Maps URLs to views	/employees/
Templates :	Generates dynamic HTML	Display employee details
Forms	Validates and processes user input	Registration form
Security	Includes protections against common web vulnerabilities	CSRF protection
Middleware	Processes requests and responses globally	Authentication checks
Migrations	Tracks database schema changes	makemigrations
Testing	Supports automated application tests	Test employee APIs
Internationalization	Supports multiple languages	English and Hindi
Async support	Supports asynchronous request handling in appropriate contexts	Async views and I/O

## How to Setup Django App

> python --version

> pip --version

> pip freeze : Check Package list

> pip install django

> django-admin startproject myproject

> python manage.py runserver

## App URL : http://127.0.0.1:8000

> python manage.py runserver 6000

## Django Directory Structure

- manage.py : main file
- template : html file
- static : css, js, Fonts, Image
- media : 

- settings.py
- urls.py
- views.py


