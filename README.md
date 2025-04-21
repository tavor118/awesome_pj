# awesome_pj 

A collection of useful links, inspired by Awesome Python and Awesome Django, but carefully crafted to avoid being overwhelming. 

## Python 

### Text Processing 

- [python-phonenumbers](https://github.com/daviddrysdale/python-phonenumbers) - parse and convert phonenumbers
- [inflection](https://github.com/jpvanhal/inflection) - string transformation library. It singularizes and pluralizes English words, and transforms strings from CamelCase to underscored string


### Datetime 

- [pendulum](https://github.com/python-pendulum/pendulum) - Python datetimes made easy
- [arrow](https://github.com/arrow-py/arrow) - better dates & times for Python 
- [dateutil](https://github.com/dateutil/dateutil) - useful extensions to the standard Python datetime features


### Dependency Management 

- [uv](https://github.com/astral-sh/uv) - an extremely fast Python package and project manager, written in Rust.
- [poetry](https://github.com/python-poetry/poetry) 
- [pipenv](https://github.com/pypa/pipenv) 


### Integrations 

- [redis-py](https://github.com/redis/redis-py) - python interface to the Redis key-value store
- [python-redis-lock](https://github.com/ionelmc/python-redis-lock) - Lock context manager implemented via redis SETNX/BLPOP
- [boto3](https://github.com/boto/boto3) - AWS SDK for Python 
- [asyncpg](https://github.com/MagicStack/asyncpg) - database interface library designed specifically for PostgreSQL and Python/asyncio
- [psycopg](https://github.com/psycopg/psycopg) - the most popular PostgreSQL adapter for Python
- [sentry-python](https://github.com/getsentry/sentry-python) - Sentry SDK for Python
- [Python.gitignore](https://github.com/github/gitignore/blob/main/Python.gitignore)


### CLI 

- [typer](https://github.com/fastapi/typer) - library for building CLI applications 
- [click](https://github.com/pallets/click/) - A package for creating beautiful command line interfaces in a composable way.


### Scraping 

- [scrapy](https://github.com/scrapy/scrapy) - web crawling and web scraping framework 
- [beautifulsoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) - providing Pythonic idioms for iterating, searching, and modifying HTML or XML
- [lxml](http://lxml.de/) - a very fast, easy-to-use and versatile library for handling HTML and XML


### Documentation

- [sphinx](https://github.com/sphinx-doc/sphinx) - Sphinx documentation generator
- [mkdocs](https://github.com/mkdocs/mkdocs) - project documentation with markdown 


### Data Analysis 

- [pandas](https://github.com/pandas-dev/pandas) - powerful Python data analysis toolkit 
- [numpy](https://github.com/numpy/numpy) - fundamental package for scientific computing with Python 
- [plotly](https://github.com/plotly/plotly.py) - interactive graphing library 

### Other 

- [more-itertools](https://github.com/erikrose/more-itertools) - More routines for operating on iterables, beyond `itertools`.



## Web Development 

 - [python-dependency-injector](https://github.com/ets-labs/python-dependency-injector) - dependency injection framework
 - [pyjwt](https://github.com/jpadilla/pyjwt) - JSON Web Token implementation in Python.


### Django 

- [django](https://github.com/django/django) 
- [django-filter](https://github.com/carltongibson/django-filter) - allowing users to declaratively add dynamic `QuerySet` filtering from URL parameters.
- [django-ninja](https://github.com/vitalik/django-ninja) - web framework for building APIs with Django and Python 3.6+ type hints


DRF

- [django-rest-framework](https://github.com/encode/django-rest-framework) - web APIs for Django 
- [djangorestframework-dataclasses](https://github.com/oxan/djangorestframework-dataclasses) - a dataclasses serializer for the Django REST Framework
- [django-rest-framework-simplejwt](https://github.com/jazzband/djangorestframework-simplejwt) - JSON web tokens for DRF


Settings

- [django-split-settings](https://github.com/sobolevn/django-split-settings) - organize Django settings into multiple files and directories. Easily override and modify settings. Use wildcards and optional settings files.
- [django-environ](https://github.com/joke2k/django-environ) - allows to utilize 12factor inspired environment variables to configure Django application
- [django-constance](https://github.com/jazzband/django-constance) - A Django app for storing dynamic settings in pluggable backends (Redis and Django model backend built in) with an integration with the Django admin app.


Models

- [django-mptt](https://github.com/django-mptt/django-mptt) - utilities for implementing Modified Preorder Tree Traversal
- [django-taggit](https://github.com/jazzband/django-taggit) - a simpler approach to tagging with Django


Development

- [django-debug-toolbar](https://github.com/jazzband/django-debug-toolbar) - display various debug information for Django
- [django-extensions](https://github.com/django-extensions/django-extensions/) - global custom management extensions for the Django (shell_plus, runserver_plus)
- [pytest-django](https://pypi.python.org/pypi/pytest-django/) - test runner using py.test
- [django-stubs](https://github.com/typeddjango/django-stubs) - contains type stubs
- [drf-spectacular](https://github.com/tfranzel/drf-spectacular) - sane and flexible OpenAPI 3 schema generation for Django REST framework
- [django-cors-headers](https://github.com/adamchainz/django-cors-headers)- If your back-end and front-end are on different servers, you need this
- [django-waffle](https://github.com/jazzband/django-waffle) - A feature flipper for Django.


Auth

- [django-allauth](https://github.com/pennersr/django-allauth) - authentication app for Django
- [dj-rest-auth](https://github.com/iMerica/dj-rest-auth) - Authentication for Django Rest Framework.


Integrations

- [django-anymail](https://github.com/anymail/django-anymail) - Django email backends and webhooks for Amazon SES, Brevo (Sendinblue), MailerSend, Mailgun, Mailjet, Postmark, Postal, Resend, SendGrid, SparkPost, Unisender Go and more
- [django-push-notifications](https://github.com/jazzband/django-push-notifications) - send push notifications to mobile devices through GCM or APNS in Django


Django Admin

- [django-grappelli](https://github.com/sehmaschine/django-grappelli) - a jazzy skin for the Django Admin-Interface


### FasAPI / Litestar

- [fastapi](https://github.com/fastapi/fastapi) 
- [litestar](https://github.com/litestar-org/litestar)
- [pydantic](https://github.com/pydantic/pydantic) - data validation using Python type hints 
- [sqlalchemy](https://github.com/sqlalchemy/sqlalchemy) - database toolkit for Python 
- [sqlmodel](https://github.com/fastapi/sqlmodel) - library for interacting with SQL databases from Python code, with Python objects
- [orjson](https://github.com/ijl/orjson) - Fast, correct Python JSON library supporting dataclasses, datetimes, and numpy
- [slowapi](https://github.com/laurentS/slowapi) - rate limiting library for Starlette and FastAPI
- [FastAPI-JSONAPI](https://github.com/mts-ai/FastAPI-JSONAPI) - JSON:API for FastAPI
- [uvloop](https://github.com/MagicStack/uvloop) - ultra fast asyncio event loop


### Task Queues

- [celery](https://github.com/celery/celery) - distributed task queue 
- [flower](https://github.com/mher/flower) - real-time monitor and web admin for Celery distributed task queue
- [Airflow](https://airflow.apache.org/) - Airflow is a platform to programmatically author, schedule and monitor workflows.


### HTTP Clients

- [stamina](https://github.com/hynek/stamina) - production-grade retries
- [tenacity](https://github.com/jd/tenacity) - general-purpose retrying library
- [httpx](https://github.com/encode/httpx) - HTTP client library. Provides both sync and async APIs 
- [aiohttp](https://github.com/aio-libs/aiohttp) - async http client/server framework
- [requests](https://github.com/psf/requests) - HTTP Requests for Humans


### WSGI 

- [gunicorn](https://github.com/benoitc/gunicorn) - Python WSGI HTTP Server 
- [uvicorn](https://github.com/encode/uvicorn) - Python ASGI web server 
- [granian](https://github.com/emmett-framework/granian) - Rust HTTP server
- [uwsgi](https://uwsgi-docs.readthedocs.io/en/latest/) - a project aims at developing a full stack for building hosting services, written in C


### Environment

- [python-dotenv](https://github.com/theskumar/python-dotenv) - reads key-value pairs from a `.env` file


## Development 

- [icecream](https://github.com/gruns/icecream) - never use print() to debug again 


### Testing 

- [pytest](https://github.com/pytest-dev/pytest) - best testing framework 
- [pytest-xdist](https://github.com/pytest-dev/pytest-xdist) - extends pytest with new test execution modes, the most used being distributing tests across multiple CPUs to speed up test execution
- [pytest-cov](https://github.com/pytest-dev/pytest-cov) - produces coverage reports
- [tox](https://tox.readthedocs.io/en/latest/) - auto builds and tests distributions in multiple Python versions
- [coverage](https://pypi.org/project/coverage/) - code coverage measurement
- [factory_boy](https://github.com/FactoryBoy/factory_boy) - test fixtures replacement for Python
- [faker](https://github.com/joke2k/faker) - a Python package that generates fake data
- [freezegun](https://github.com/spulec/freezegun) - travel through time by mocking the datetime module
- [time-machine](https://github.com/adamchainz/time-machine) - travel through time in your tests. Faster than freezegun.
- [responses](https://github.com/getsentry/responses) - a utility library for mocking out the requests Python library
- [fakeredis-py](https://github.com/cunla/fakeredis-py) - pure-Python implementation of the Redis protocol API


### Linters and Formatters

- [Ruff](https://github.com/astral-sh/ruff) - an extremely fast Python linter and code formatter, written in Rust
- [isort](https://github.com/PyCQA/isort) - utility to sort imports
- [flake8](https://github.com/PyCQA/flake8) - a wrapper around`pycodestyle`,`pyflakes`and McCabe
- [flake8-print](https://github.com/JBKahn/flake8-print) - check for Print statements in python files
- [black](https://github.com/psf/black) - The uncompromising Python code formatter.
- [pre-commit](https://github.com/pre-commit/pre-commit) - framework for managing and maintaining multi-language pre-commit hooks 
- [mypy](https://github.com/python/mypy) - static typing for Python 




## Interview 

- [pj_python_interview_questions_and_answers](https://tavor118.github.io/pj_python_interview_questions_and_answers) - python Interview Questions and Answers 
- [system-design-primer](https://github.com/donnemartin/system-design-primer) - prep for the system design interview. Includes Anki flashcards. 


## Other collections 

- [awesome-python](https://github.com/uhub/awesome-python) 
- [awesome-django](https://github.com/wsvincent/awesome-django) 
- [python-cheatsheet](https://github.com/gto76/python-cheatsheet) - comprehensive python cheatsheet
