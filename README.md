A Nanobox Build for Python 3 Falcon Applications that leverages [admiralobvious's](https://github.com/admiralobvious/falcon-boilerplate) boilerplate.

A Python 3 boilerplate for the [Falcon](https://github.com/falconry/falcon) framework. Uses [gunicorn](https://github.com/benoitc/gunicorn) as the WSGI HTTP server and [meinheld](https://github.com/mopemope/meinheld) as the gunicorn worker. It also uses [Vyper](https://github.com/admiralobvious/vyper) for [12-factor](https://12factor.net/).

## Quick Start

```
$ git clone https://github.com/admiralobvious/falcon-boilerplate.git myapp
$ cd myapp
$ nanobox run
$ python run.py
```

To run the tests:

```
$ nose2 tests
```

For Local Development:

From inside a Nanobox terminal:

```
$ pip install -r dev_requirements.txt
```
