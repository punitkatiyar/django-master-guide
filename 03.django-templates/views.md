# Django Views


```py
from django.shortcuts import render
from django.http import HttpResponse

# Create your View

def home(request):
    return HttpResponse("hello App")

def page(request):
    return HttpResponse("<h1>Page App</h1>")
```
