Installation
==========

Installing: 

    easy_install django-startappextracontext

or:

    pip install django-startappextracontext

Then add `startappextracontext` to your `INSTALLED_APPS`:

    INSTALLED_APPS = (
        #... your other apps

        ('startappextracontext'),
    )

Example usage
===========

To create an new app called `my_stuff` from a custom template residing in `~/my-custom-app-template` with the 
custom variable `model_name` with value `Stuff` you can do the following:

    ./manage.py startappextracontext --template=~/my-custom-app-template --extra-context=[model_name]Stuff my_stuff
