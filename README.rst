django-chunked-upload demo
==========================

This examples is based on Django demo project of the `django-chunked-upload <https://github.com/juliomalegria/django-chunked-upload>`__ module.

Live demo
---------

To see a live demo of the project go to: `django-chunked-upload.juliomalegria.com <http://django-chunked-upload.juliomalegria.com>`__.

Try it locally
--------------

1. Clone the repo.

::

    git clone https://github.com/clara081094/chunck_django_example.git
    cd django-chunked-upload-demo/

2. Install the requirements (I suggest using a virtualenv).

::

    virtualenv ven
    source venv/bin/activate
    pip install -r requirements.txt

3. Create the tables.

::

    ./manage.py migrate

4. Run the server.

::

    ./manage.py runserver

5. Go to `127.0.0.1:8000 <http://127.0.0.1:8000>`__ and upload a file.

Support
-------

If you find any bug or you want to propose a new feature, please use the `issues tracker <https://github.com/juliomalegria/django-chunked-upload/issues>`__. I'll be happy to help you! :-)
