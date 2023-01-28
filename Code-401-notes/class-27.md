# Class 27 - Django Models

## Reading

### Using Models
[Source Credit](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Models)
- Django web applications access and manage data through Python objects referred to as models
- Models define the structure of stored data
- the definition of the model is independent of the underlying database — you can choose one of several as part of your project settings.
- Models are usually defined in an application's models.py file
- They are implemented as subclasses of `django.db.models.Model`, and can include fields, methods and metadata
- a model can have methods and should minimally include the `__str__()` method to return a string for each object.

### Django Admin
[Source Credit](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Admin_site)
- The Django admin application can use your models to automatically build a site area that you can use to create, view, update, and delete records
- you can create a superuser account that has permissions to change all our objects
- is accessed at the /admin URL
- we can add, edit and manipulate our models by installed application

## Things I want to know more about

- Common models we will want to get comfortable with