# Django

<br>

## Getting started with Django

### To start a new project

  `django-admin startproject <project name>`
  
### To create new app

  `py manage.py startapp <app name>`
  
### To create SuperUser

  `py manage.py createsuperuser`
  
### Migrations

  `py manage.py makemigrations` (after changing in database)
  
  `py manage.py migrate`
  
<br>

## Instructions

Note: Dont forgot to import necessary stuff 

* Add your app in `INSTALLED APPS` in `settings.py`.
* Update paths in `urls.py` <br>
  e.g.
  ```
  urlpatterns = [
    path('', views.home, name='shop-home'),
    path('home/', views.home, name='shop-home'),
  ]
  ```
* define path functions in `views.py` <br>
  e.g.
  ```
  def home(request):
    return render(request, 'index.html')
  ```
* 
  
