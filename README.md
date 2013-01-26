PPI Documentation
=================

The PPI Framework documentation for version 2.1+ (work in progress).

[![Build Status](https://travis-ci.org/noiselabs/ppi-docs.png?branch=master)](https://travis-ci.org/noiselabs/ppi-docs)

Documentation Format
--------------------

The PPI2 documentation uses [reStructuredText](http://docutils.sourceforge.net/rst.html) as its markup language and
[Sphinx](http://sphinx-doc.org/) for building the output (HTML, PDF, ...).

Please refer to both project homepages to learn it's syntax if you're not used with reST/Sphinx yet.

Generating the Documentation
----------------------------

To build the documentation you'll need Python and Sphinx installed.

```bash
$ apt-get install python2.7
$ easy_install sphinx
$ cd /path/to/ppi-docs
$ composer install
$ make html
```

Contributing
------------

The PPI2 documentation is hosted on GitHub:

    https://github.com/noiselabs/ppi-docs

To submit a contribution, fork the official repository on GitHub and send a [Pull Request](https://help.github.com/articles/using-pull-requests).

Like PPI Framework source code, the documentation repository is split into two branches: 2.1 for the current PPI 2.1.x release and master as the development branch for upcoming releases.

Translations
------------

Contributing translations requires that you make a new directory using the two letter name for your language. As content is translated, directories mirroring the english content should be created with localized content.
