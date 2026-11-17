# Django Views


```py
from django.shortcuts import render
from django.http import HttpResponse

# Create your View

def hello(request):
    return HttpResponse("hello App")
```
