## Views

### Create a view

```
def index(request):
    return HttpResponse("Hello, world!")

```

Now we need to creat ea urls.py and indicate where we are going to use it

```
urlpatterns = [path("", views.index, name="index")]
```

Here we are giving an extra parameter a name that will be useful for links and future interaction.

Now we need to head to the project's urls.py file and register this app route:

```
urlpatterns = [path("admin/", admin.site.urls), 
       path("hello/", include("hello.urls"))]
```
