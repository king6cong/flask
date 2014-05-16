# Flask

Web development, one drop at a time


## What is Flask?

Flask is a microframework for Python based on Werkzeug
and Jinja2.  It's intended for getting started very quickly
and was developed with best intentions in mind.

## Is it ready?

It's still not 1.0 but it's shaping up nicely and is
already widely used.  Consider the API to slightly
improve over time but we don't plan on breaking it.

## What do I need?

Jinja 2.4 and Werkzeug 0.7 or later.
`pip` or `easy_install` will install them for you if you do
`pip install Flask`. I encourage you to use a virtualenv.
Check the docs for complete installation and usage
instructions.

## Where are the docs?

Go to http://flask.pocoo.org/docs/ for a prebuilt version
of the current documentation.  Otherwise build them yourself
from the sphinx sources in the docs folder.

## Where are the tests?

Good that you're asking.  The tests are in the
flask/testsuite package.  To run the tests use the
`run-tests.py` file:

    $ python run-tests.py

If it's not enough output for you, you can use the
`--verbose` flag:

    $ python run-tests.py --verbose

If you just want one particular testcase to run you can
provide it on the command line:

    $ python run-tests.py test_to_run

## Where can I get help?

Either use the #pocoo IRC channel on irc.freenode.net or
ask on the mailinglist: http://flask.pocoo.org/mailinglist/

See http://flask.pocoo.org/community/ for more resources.

Why?

this is new

