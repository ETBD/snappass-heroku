========
SnapPass
========

|pypi| |build|

.. |build| image:: https://travis-ci.org/samteezy/snappass-heroku.svg
    :target: http://travis-ci.org/samteezy/snappass-heroku
    :alt: Build status

It's like SnapChat... for Passwords... (for Heroku).

If you want to read more about how it works, go check out the `original`_ from the great folks at Pinterest: they detail security as well as available configuration options. We are simply modifying it for Heroku, plus maybe a couple more additional features ;)

Let's say you have a password.  You want to give it to your coworker, Jane.
You could email it to her, but then it's in her email, which might be backed up,
and probably is in some storage device controlled by the NSA.

See it in action and use it yourself at https://snappass.heroku.com.

.. _original: https://github.com/pinterest/snappass

Requirements
------------

* Redis
* Python 2.7+ or 3.4+ (both included)

Installation
------------

::

    $ pip install snappass
    $ snappass
    * Running on http://0.0.0.0:5000/
    * Restarting with reloader

That's it!

