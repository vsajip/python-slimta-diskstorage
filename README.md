#### [Project Homepage][1]
#### [API Documentation][2] and [Manual][3]

--------------------

About
=====

Adds a filesystem-based queue extension to python-slimta. This is a storage
plugin for the standard queue engine that uses asynchronous file system
operations (via [aio][4]) to store and load messages and message metadata to
disk.

[![Build Status](http://ci.slimta.org/job/python-slimta-diskstorage/badge/icon)](http://ci.slimta.org/job/python-slimta-diskstorage/)

Getting Started
===============

If you haven't yet installed [`python-slimta`][5], refer to the "Getting
Started" section. Once inside your virtualenv:

    (.venv)$ python setup.py develop

To run the suite of included unit tests:

    (.venv)$ nosetests

Refer to the [API Documentation][2] and [Manual][3] for more information on
using this extension.

[1]: http://slimta.org/
[2]: http://docs.slimta.org/latest/api/extra.diskstorage.html
[3]: http://docs.slimta.org/latest/manual/extensions.html#disk-storage
[4]: http://man7.org/linux/man-pages/man7/aio.7.html
[5]: https://github.com/slimta/python-slimta

