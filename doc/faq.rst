Frequently asked questions
==========================

Why did my test coverage measurement stop working?
--------------------------------------------------

MonkeyType uses the same `sys.setprofile`_ hook that `coverage.py`_ uses to
measure Python code coverage, so you can't use MonkeyType and coverage
measurement together. If you want to run your tests under MonkeyType tracing,
disable coverage measurement for that run, and vice versa.

.. _coverage.py: https://coverage.readthedocs.io/
.. _sys.setprofile: https://docs.python.org/3/library/sys.html#sys.setprofile
