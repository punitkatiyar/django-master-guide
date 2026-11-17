# Django Routing

```py
from django.contrib import admin
from django.urls import path
from blog import views

urlpatterns = [
    path('admin/', admin.site.urls),
    path('', views.home, name='home')
]

```


## manage multiple app in django

```py
from blog import views as b1 

urlpatterns = [
    path('', b1.home, name='home')
]
```
