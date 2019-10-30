===========================
cookiecutter-python-package
===========================

This is a Cookiecutter template for a Python package that tries to follow
the current best practices from the `Python Packaging User Guide`_ while
including configuration for some helpful extra tools.

This is a fork of https://github.com/audreyr/cookiecutter-pypackage

See https://github.com/audreyr/cookiecutter for instructions for using
Cookiecutter.

The new project will be configured with the following by default:

* Free software: MIT license
* Vanilla testing setup with `unittest` and `python setup.py test`
* Travis-CI_: Ready for Travis Continuous Integration testing
* Tox_ testing: Setup to easily test for Python 2.7, 3.3, 3.4, 3.5, pypy
* Sphinx_ docs: Documentation ready for generation with, for example, ReadTheDocs_
* Click: It will install click as a dependency and include a CLI entry point by default. It's easier (for me at least) to delete this when not needed than it is to maintain a seperate branch.

Usage
-----

Generate a Python package project::

    cookiecutter https://github.com/vanangamudi/cookiecutter-python-package.git

Then:

* Create a repo and put it there.
* Add the repo to your Travis CI account.
* Add the repo to your ReadTheDocs account + turn on the ReadTheDocs service hook.
* Release your package the standard Python way. Here's a release checklist: 
  https://gist.github.com/audreyr/5990987

Not Exactly What You Want?
--------------------------

Don't worry, you have options:

Similar Cookiecutter Templates
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

* `Nekroze/cookiecutter-pypackage`_: A fork of this with a PyTest test runner,
  strict flake8 checking with Travis/Tox, and some docs and `setup.py` differences.
  
* `tony/cookiecutter-pypackage-pythonic`_: Fork with py2.7+3.3 optimizations. 
  Flask/Werkzeug-style test runner, ``_compat`` module and module/doc conventions.
  See ``README.rst`` or the `github comparison view`_ for exhaustive list of 
  additions and modifications.

* Also see the `network`_ and `family tree`_ for this repo. (If you find
  anything that should be listed here, please add it and send a pull request!)

Fork This / Create Your Own
~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you have differences in your preferred setup, I encourage you to fork this
to create your own version. Or create your own; it doesn't strictly have to
be a fork.

* Once you have your own version working, add it to the Similar Cookiecutter
  Templates list above with a brief description. 

* It's up to you whether or not to rename your fork/own version. Do whatever
  you think sounds good.

Or Submit a Pull Request
~~~~~~~~~~~~~~~~~~~~~~~~

I also accept pull requests on this, if they're small, atomic, and if they
make my own packaging experience better.


.. _Travis-CI: http://travis-ci.org/
.. _Tox: http://testrun.org/tox/
.. _Sphinx: http://sphinx-doc.org/
.. _ReadTheDocs: https://readthedocs.org/
.. _`Nekroze/cookiecutter-pypackage`: https://github.com/Nekroze/cookiecutter-pypackage
.. _`tony/cookiecutter-pypackage-pythonic`: https://github.com/tony/cookiecutter-pypackage-pythonic
.. _github comparison view: https://github.com/tony/cookiecutter-pypackage-pythonic/compare/audreyr:master...master
.. _`network`: https://github.com/audreyr/cookiecutter-pypackage/network
.. _`Python Packaging User Guide`: https://packaging.python.org/en/latest/index.html
.. _`family tree`: https://github.com/audreyr/cookiecutter-pypackage/network/members
