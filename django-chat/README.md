# django_chat

## Installation

~~~
> pipenv install https://github.com/genosltd/django-chat
~~~

## Usage

Do not forget to list `django-chat` in `settings.py`:

~~~python
# settings.py
INSTALLED_APPS = [
    'django-chat',
]
~~~

### Models

### Admin


### Testing

For testing please use:

~~~
> pipenv run tests\runtests.py
~~~

or with coverage:

~~~
> pipenv run coverage run --source django_chat tests\runtests.py
~~~

and then for html coverage report (in `htmlcov`):

~~~
> pipenv run coverage html
~~~

