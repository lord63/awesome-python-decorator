# Awesome Python Decorator

> A curated list of awesome python decorator resources.

## You don't know decorator

Here are some resources about the python decorators.

- [PEP 0318 -- Decorators for Functions and Methods](https://www.python.org/dev/peps/pep-0318/)
- [PEP 3129 -- Class Decorators](https://www.python.org/dev/peps/pep-3129/)
- [Python Wiki - PythonDecorators](https://wiki.python.org/moin/PythonDecorators) This page largely documents the
history of the process of adding decorators to Python.
- [Python Wiki - PythonDecoratorLibrary](https://wiki.python.org/moin/PythonDecoratorLibrary) This page is meant
to be a central repository of decorator code pieces. Lots of decorator examples, really cool!

## Built-in python decorator

- [@abc.abstractmethod](https://docs.python.org/3.5/library/abc.html#abc.abstractmethod) A decorator indicating
abstract methods.
- [@abc.abstractproperty](https://docs.python.org/3.5/library/abc.html#abc.abstractproperty) A subclass of the built-in
`property()`, indicating an abstract property.
- [@asyncio.coroutine](https://docs.python.org/3.5/library/asyncio-task.html#asyncio.coroutine) Decorator to mark
generator-based coroutines. New in version 3.4.
- [@atexit.register](https://docs.python.org/2.7/library/atexit.html#atexit.register) Register func as a function to
be executed at termination.
- [@classmethod](https://docs.python.org/3.5/library/functions.html#classmethod) Return a class method for function.
- [@contextlib.contextmanager](https://docs.python.org/3.5/library/contextlib.html#contextlib.contextmanager) Define a
factory function for with statement context managers, without needing to create a class or separate `__enter__()` and
`__exit__()` methods.
- [@functools.cached_property](https://docs.python.org/3.8/library/functools.html#functools.cached_property) Transform
a method of a class into a property whose value is computed once and then cached as a normal attribute
for the life of the instance.
- [@functools.lru_cache](https://docs.python.org/3.5/library/functools.html#functools.lru_cache) Decorator to wrap a
function with a memoizing callable that saves up to the maxsize most recent calls. It can save time when an expensive
or I/O bound function is periodically called with the same arguments. New in python 3.2.
- [@functools.singledispatch](https://docs.python.org/3.5/library/functools.html#functools.singledispatch) Transforms
a function into a single-dispatch generic function. New in python 3.4.
- [@functools.total_ordering](https://docs.python.org/3.5/library/functools.html#functools.total_ordering) Given a
class defining one or more rich comparison ordering methods, this class decorator supplies the rest.
- [@functools.wraps](https://docs.python.org/3.5/library/functools.html#functools.wraps) This is a convenience function
for invoking update_wrapper() as a function decorator when defining a wrapper function.
- [@property](https://docs.python.org/3.5/library/functions.html#property) Return a property attribute.
- [@staticmethod](https://docs.python.org/3.5/library/functions.html#staticmethod) Return a static method for function.
- [@types.coroutine](https://docs.python.org/3.5/library/types.html#types.coroutine) This function transforms a
generator function into a coroutine function which returns a generator-based coroutine. New in python 3.5.
- [@unittest.mock.patch](https://docs.python.org/3.5/library/unittest.mock.html#unittest.mock.patch) Acts as a function
decorator, class decorator or a context manager. Inside the body of the function or with statement, the target is
patched with a new object. When the function/with statement exits the patch is undone. New in python 3.3.
- [@unittest.mock.patch.dict](https://docs.python.org/3.5/library/unittest.mock.html#unittest.mock.patch.dict)
Patch a dictionary, or dictionary like object, and restore the dictionary to its original state after the test.
New in python 3.3.
- [@unittest.mock.patch.multiple](https://docs.python.org/3.5/library/unittest.mock.html#unittest.mock.patch.multiple)
Perform multiple patches in a single call. New in python 3.3.
- [@unittest.mock.patch.object](https://docs.python.org/3.5/library/unittest.mock.html#unittest.mock.patch.object)
Patch the named member (attribute) on an object (target) with a mock object. New in python 3.3.
- to be continue


## Python decorator in the wild

Once you know the basics of how to use a decorator, you can take a look at some real projects to see how people use
decorators in real life.

- [cached-property](https://github.com/pydanny/cached-property) A decorator for caching properties in classes.
- [cachetools](https://github.com/tkem/cachetools) This module provides various memoizing collections and decorators,
including variants of the Python 3 Standard Library @lru_cache function decorator.
- [celery](https://github.com/celery/celery) Celery is a distributed task queue, it uses decorator to create tasks.
- [click](https://github.com/mitsuhiko/click) Click is a Python package for creating beautiful command line interfaces,
based on declaring commands through decorators. You can also check out the
[autocommand](https://github.com/Lucretiel/autocommand) library which shares a similar idea with click.
- [deco](https://github.com/alex-sherman/deco) A simplified parallel computing model for Python. DECO automatically
parallelizes Python programs, and requires minimal modifications to existing serial programs.
- [decorator](https://github.com/micheles/decorator) This is your best option if you want to preserve the signature of
decorated functions in a consistent way across Python releases.
- [deprecated](https://github.com/tantale/deprecated) Use `@deprecated` decorator to deprecate old python classes,
  functions or methods. Decorators can also be used to add Sphinx directives.
- [fasteners](https://github.com/harlowja/fasteners) Provides useful locks and decorators to lock/unlock around functions and methods.
- [flask](https://github.com/mitsuhiko/flask) Flask is a micro web framework in python, which uses decorators to route
the URL, register error handler, register processor and so on.
- [flask-login](https://github.com/maxcountryman/flask-login) Flask-Login provides user session management for Flask.
For example, it use the `login_required` decorator to protect some views that need the user to be logged in.
- [GB2260.py](https://github.com/cn/GB2260.py) This project is used to look up Chinese administrative divisions. It
uses decorators to write Python 2.x and 3.x compatible code.
- [marshmallow](https://github.com/marshmallow-code/marshmallow) A lightweight library for converting complex objects
to and from simple Python datatypes. It use decorators to register schema pre-processing and post-processing methods.
- [me-api](https://github.com/lord63/me-api) An extensible, personal API with custom integrations. It uses a decorator
to make sure there is an access_token in the configuration file before sending the API request and reject another
authentication if there is already an access_token.
- [numba](https://numba.pydata.org/) Numba gives you the power to speed up your applications with high performance functions written directly in Python. It uses `jit` to decorate array-oriented and math-heavy Python code can be just-in-time compiled to native machine instructions, similar in performance to C, C++ and Fortran, without having to switch languages or Python interpreters.
- [lettuce](https://github.com/gabrielfalcao/lettuce) Lettuce is a BDD tool for python. It uses `step` and `steps` to
decorate functions and classes so they become new step definitions.
- [profilehooks](https://github.com/mgedmin/profilehooks) Python decorators for profiling/tracing/timing a single
function.
- [pypi-cli](https://github.com/sloria/pypi-cli) pypi-cli is a command-line interface to the Python Package Index.
It use decorator to makes a property lazy-evaluated.
- [py-spin](https://github.com/lord63/py-spin) py-spin is a terminal spinner package for python. Yes, it does use a
decorator to register a function that needs to take a long time to finish, as well as showing a spinner while it's
processing!
- [python-goto](https://github.com/snoack/python-goto) A function decorator that rewrites the bytecode, enabling goto
in python.
- [showme](https://github.com/kennethreitz/showme) ShowMe is a simple set of extremely useful function decorators for Python.
It allows you to view trace information, execution time, cputime, and function documentation.
- [tenacity](https://github.com/jd/tenacity) Simplifies the task of adding retry behavior to just about anything. It originates from a fork of [retrying](https://github.com/rholder/retrying).
- [timeout-decorator](https://github.com/pnpnpn/timeout-decorator) Timeout decorator for Python which uses a decorator
to limit the execution time of the given function.
- [Tomorrow](https://github.com/madisonmay/Tomorrow) Tomorrow use decorator to do the magic that let you write
asynchronous code with ease.
- [wrapt](https://github.com/GrahamDumpleton/wrapt) A Python module for decorators, wrappers and monkey patching.

## Contribute

Please do! Create a project is not hard, while maintaining it is not easy. To make this project stay healthy and easy
to maintain, what's more, to make it to be AWESOME, we need help. The best way in my opinion is watch this repository
and join the daily discussions when some send a pull request and raise an issue. There are also many other ways to
do the contribution, but please read the [Contributing guide][] before stepping forward :)

Contributions are always welcome at any time! :sparkles: :cake: :sparkles:

## License

CC0 1.0

[Contributing guide]: https://github.com/lord63/awesome-python-decorator/blob/master/CONTRIBUTING.md
