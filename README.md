# Django User Model customized:

This is an exampel of how you can implement the authentication
with email and password.

**This example is written with Django 3.2**

## Building

It is best to use the python `virtualenv` tool to build locally:

```sh
$ virtualenv-2.7 venv
$ source venv/bin/activate
$ pip install -r requirements.txt
$ DEVELOPMENT=1 python manage.py runserver

Then visit `http://localhost:8000` to view the app. Alternatively you
can use foreman and gunicorn to run the server locally (after copying
`dev.env` to `.env`):

```sh
$ foreman start
```

## Get involved!

We are happy to receive bug reports, fixes, documentation enhancements,
and other improvements.

Please report bugs via the
[github issue tracker](https://github.com/crlalbu/djangoum3/issues).

Master [git repository](https://github.com/crlalbu/djangoum3):

* `git clone https://github.com/crlalbu/djangoum3`

## Licensing

This library is BSD-licensed.

