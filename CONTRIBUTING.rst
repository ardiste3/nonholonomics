============
Contributing
============

This project is no where near finished. If you would like to contribute 
see the options below.


Types of Contributions
----------------------

Report Bugs
~~~~~~~~~~~

Report bugs at https://github.com/ardiste3/nonholonomics/issues.

Please include:

* Any details about your local setup that might be helpful in troubleshooting.
* Detailed steps to reproduce the bug.

Fix Bugs
~~~~~~~~

Look through the gitlab for bugs. Anything tagged with "bug"
is open to whoever wants to attempt to fix it.

Implement Features
~~~~~~~~~~~~~~~~~~

Look through the gitlab issues for features. Anything tagged with "feature"
is open to whoever wants to try to tackle it.

Write Documentation
~~~~~~~~~~~~~~~~~~~

nonholonomics could always use more documentation, whether
as part of the official nonhlonomics docs, in docstrings,
or simple comments

Submit Feedback
~~~~~~~~~~~~~~~

The best way to send feedback is to file an issue at https://github.com/ardiste3/nonholonomics/issues.

If you are proposing a feature:

* Explain in detail how it would work.
* Keep the scope as broad as possible, to keep it as robust as possible.

Get Started!
------------

Ready to contribute? Here's how to set up `nonhlonomics` for local development.

1. Fork the `nonholonomics` repo on GitHub.
2. Clone your fork locally::

    $ git clone https://github.com/ardiste3/nonholonomics

3. Install your local copy into a virtualenv. Assuming you have virtualenvwrapper installed, this is how you set up your fork for local development::

    $ mkvirtualenv nonhlonomics
    $ cd nonhlonomics/
    $ python setup.py develop

4. Create a branch for local development::

    $ git checkout -b name-of-your-bugfix-or-feature

   Now you can make your changes locally.

5. When you're done making changes, check that your changes pass flake8 and the tests, including testing other Python versions with tox::

    $ flake8 nonhlonomics tests
    $ python setup.py test
    $ tox

   To get flake8 and tox, just pip install them into your virtualenv.

6. Commit your changes and push your branch to GitHub::

    $ git add .
    $ git commit -m "Your detailed description of your changes."
    $ git push origin name-of-your-bugfix-or-feature

7. Submit a pull request through the GitHub website.

Pull Request Guidelines
-----------------------

Before you submit a pull request, check that it meets these guidelines:

1. The pull request should include tests.
2. If the pull request adds functionality, the docs should be updated. Put
   your new functionality into a function with a docstring, and add the
   feature to the list in README.rst.