# Awesome Python Decorator

> A curated list of awesome python decorator resources.

## You don't know decorator

Here are some resources about the python decorators.

- [PEP 0318 -- Decorators for Functions and Methods](https://www.python.org/dev/peps/pep-0318/)
- [PEP 3129 -- Class Decorators](https://www.python.org/dev/peps/pep-3129/)
- [Python Wiki - PythonDecorators](https://wiki.python.org/moin/PythonDecorators) This page largely documents the
history of the process of adding decorators to Python.
- [Python Wiki - PythonDecoratorLibrary](https://wiki.python.org/moin/PythonDecoratorLibrary) This page is meant
to be a central repository of decorator code pieces. Lots of decorator example, really cool!

## Python decorator in the wild

Once you've know the basic of how to use the decorator, now you can take a look at some projects to see how people use
decorator in real life.

- [cached-property](https://github.com/pydanny/cached-property) A decorator for caching properties in classes.
- [cachetools](https://github.com/tkem/cachetools) This module provides various memoizing collections and decorators,
including variants of the Python 3 Standard Library @lru_cache function decorator.
- [celery](https://github.com/celery/celery) Celery is a distributed task queue, it uses decorator to create tasks.
- [click](https://github.com/mitsuhiko/click) Click is a Python package for creating beautiful command line interfaces,
based on declaring commands through decorators.
- [decorator](https://github.com/micheles/decorator) It is your best option if you want to preserve the signature of
decorated functions in a consistent way across Python releases.
- [Flask](https://github.com/mitsuhiko/flask) Flask is a micro web framework in python, it use decorator to route the
URL, register error handler, register processor and so on.
- [flask-login](https://github.com/maxcountryman/flask-login) Flask-Login provides user session management for Flask.
For example, it use the `login_required` decorator to protect some views that need the users to be logged in.
- [GB2260.py](https://github.com/cn/GB2260.py) It is used to look up Chinese administrative divisions. It use the
decorator to do the python 2.x and 3.x compatible mission.
- [marshmallow](https://github.com/marshmallow-code/marshmallow) A lightweight library for converting complex objects
to and from simple Python datatypes. It use decorators to register schema pre-processing and post-processing methods.
- [me-api](https://github.com/lord63/me-api) An extensible, personal API with custom integrations. It use the decorator
to make sure there is an access_token in the configuration file before sending the API request and reject another
authentication if there is already an access_token.
- [lettuce](https://github.com/gabrielfalcao/lettuce) Lettuce is a BDD tool for python, it use `step` and `steps` to
decorator functions and class so that it will become a new step definitio.
- [profilehooks](https://github.com/mgedmin/profilehooks) Python decorators for profiling/tracing/timing a single
function.
- [pypi-cli](https://github.com/sloria/pypi-cli) pypi-cli is a command-line interface to the Python Package Index.
It use decorator to makes a property lazy-evaluated.
- [py-spin](https://github.com/lord63/py-spin) py-spin is a terminal spinner package for python. Yes, it use decorator
to register a function that need to take a long time to finish and show the spinner when process it.
- [python-goto](https://github.com/snoack/python-goto) A function decorator, that rewrites the bytecode, to enable goto
in python.
- [retrying](https://github.com/rholder/retrying) Retrying is general-purpose retrying library simplify the task of
adding retry behavior to just about anything.
- [timeout-decorator](https://github.com/pnpnpn/timeout-decorator) Timeout decorator for Python, it use decorator to
limit the execution time of the given function.
- [Tomorrow](https://github.com/madisonmay/Tomorrow) Tomorrow use decorator to do the magic that let you write
asynchronous code with ease.
- [wrapt](https://github.com/GrahamDumpleton/wrapt) A Python module for decorators, wrappers and monkey patching.

## Contribute

Please do! Create a project is not hard, while maintaining it is not easy. To make this project stay healthy and easy
to maintain, what's more, to make it to be AWESOME, we need help. The best way in my opinion is watch this repository
and join the daily discussions when some send a pull request and raise an issue. There are also many other ways to
do the contribution, but please read the [Contributing guide][] before step forward :)

Contributions are always welcome at any time! :sparkles: :cake: :sparkles:

## License

CC0 1.0

[Contributing guide]: https://github.com/lord63/awesome-python-decorator/blob/master/CONTRIBUTING.md
