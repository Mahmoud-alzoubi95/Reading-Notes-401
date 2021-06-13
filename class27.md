# Django Models

Django web applications access and manage data through Python objects referred to as models. Models define the structure of stored data, including the field types and possibly also their maximum size, default values, selection list options, help text for documentation, label text for forms.  

## Designing the LocalLibrary models
![](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Models/local_library_model_uml.svg)

### Model definition
Models are usually defined in an application's models.py file. They are implemented as subclasses of django.db.models.Model, and can include fields, methods and metadata.

### Defining the LocalLibrary Models
In this section we will start defining the models for the library. Open models.py (in /locallibrary/catalog/). The boilerplate at the top of the page imports the models module,<br> which contains the model base class models.Model that our models will inherit from.


* Genre model
* Book model
* BookInstance model
* Author model


# Django admin site
The Django admin application can use your models to automatically build a site area that you can use to create, view, update, and delete records. This can save you a lot of time during development, making it very easy to test your models and get a feel for whether you have the right data. The admin application can also be useful for managing data in production, depending on the type of website.




