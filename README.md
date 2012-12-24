# Django CMS Quickstart
You don't like all the hassle installing django-cms?The solution is right here.

Currently for django-cms version 2.3.5

# Setup
Do the following in a terminal:

    git clone git://github.com/JonasGroeger/django_cms_quickstart.git
    cd django_cms_quickstart/
    mkvirtualenv djangocmsquickstart
    pip install -r requirements.txt
    # Get a cup of coffee and some salad
    python manage.py syncdb --all
    python manage.py migrate --fake
    python manage.py runserver

And there you have your running django-cms on localhost :)

# License
Licensed under [CC-BY-SA 3.0](http://creativecommons.org/licenses/by-sa/3.0/de/).
