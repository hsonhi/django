This sample contains the completed program from the tutorial, [Using Django in Visual Studio Code](https://code.visualstudio.com/docs/python/tutorial-django). Intermediate steps are not included.

The sample also includes a Dockerfile to build a production-ready container image that uses uwsgi and nginx; the uwsgi.ini file provides uwsgi configuration.

To run the sample:

1. Create a virtual environment as described in the tutorial.
1. Install packages with `pip install -r requirements.txt`.
1. Activate the virtual environment by running `source env/bin/activate` (Linux/MacOS) or `env\scripts\activate` (Windows).
1. Create and initialize the database by running `python manage.py migrate`.
1. Create a superuser as described at the end of the tutorial.
