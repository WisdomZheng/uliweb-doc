# Installation


## Requirement


* Python 2.5+
* setuptools 0.6c9


## Extra Requirement


* SQLAlchemy 0.6+ (If you want to use Uliweb ORM you should install it)
* pytz (Used in uliweb.utils.date and ORM for timezone process)


## Installation


1. easy_install Uliweb
1. Download Uliweb package from [http://code.google.com/p/uliweb/downloads/list](http://code.google.com/p/uliweb/downloads/list) or
    get the source files from svn:

    ```
    svn checkout http://uliweb.googlecode.com/svn/trunk/ uliweb
    ```

1. In uliweb installation directory, run `setup.py` to install it:

    ```
    python setup.py develop
    ```

    This command will install a link of the current Uliweb directory to the Python
    site-packages directory. , and you can find an entry in easy_install.pth.
    This command will also install a script named `uliweb` to Python/Scripts
    directory. Make sure that you have added the Python and Python/Scripts directories
    to your systems search path(adding the new path to the PATH environment). Doing this allows you
    to run the uliweb scripts anywhere on te commandline.

    {% alert class=info %}
    Why not use `python setup.py install`? The `uliweb` script
    can't be installed correctly using this method, I will appreciate if someone can help with this issue.
    {% endalert %}

1. 
    After above steps, run `uliweb` command in command line and see the tutorials --
    to learn how to use `uliweb` for web application development.



