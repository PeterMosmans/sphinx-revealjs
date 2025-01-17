===========
Change logs
===========

ver 1.1.0
=========

:date: 2021-04-04
:base: Reveal.js 4.1.0

New features
------------

* Add option to add ``id`` attribute per sections (#59, #61)

  * Supporting label syntax of Sphinx.

Extra
-----

* Fix dependencies for development environment
* Add ``package.json`` to notify updates reveal.js by dependabot

ver 1.0.1
=========

:date: 2021-01-30
:base: Reveal.js 4.1.0

Fixes
-----

- Change order of link tags for css files (#40, #41)
- Rename test case function names for duplicated (#42, #54)

ver 1.0.0
=========

:date: 2021-01-03
:base: Reveal.js 4.1.0

Breaking changes
----------------

In this version, ``sphinx-revealjs`` bundle Reveal.js version 4.x,
and does not supporting to work with Reveal.js 3.x.

If you want to migrate presentation source for this version,
please see `migration example <./docs/migrations>`_. 

New features
------------

* Using Revealjs 4.x (use 4.1.0)

  * With supporting multiple presentation management in single documentation

Drop
----

* Bundle and implements for Revealjs 3.x

ver 0.12.1
==========

:date: 2020-12-12

Fixes
-----

* Restrict effect of ``revealjs_section`` for only one section ( `PR#36 <https://github.com/attakei/sphinx-revealjs/pull/36>`_ )

ver 0.12.0
==========

:date: 2020-06-21

New features
------------

* Config variables:

  * ``revealjs_js_files``
  * ``revealjs_css_files``
  * ``revealjs_static_path``

Updates
-------

* ``revealjs_google_fonts`` use Google Fonts API version 2
* Change css selector for google-fonts

Drop
----

* Remove ``zenburn.css`` from default included css files
* Ignore ``html_js_files``, ``html_css_files`` and ``html_static_path``

ver 0.11.0
==========

:date: 2020-04-17

Features
--------

* | Add new config variables ``revealjs_style_theme``,
  | ``revealjs_google_fonts``,``revealjs_generic_font``,
  | ``revealjs_script_files``, ``revealjs_script_conf``
  | and ``revealjs_script_plugins``
* | **Breaking:** Change directive option,
  | from ``config`` to ``conf`` in ``RevealjsSlide`` directive.

Drop
----

* | **Breaking:** Remove config variables
  | ``revealjs_theme`` and ``revealjs_theme_options``.

Fixes
-----

* Use black for formatting

ver 0.10.1
==========

:date: 2020-04-09

Fixes
-----

* Change bundle Reveal.js (3.9.1 -> 3.9.2)

ver 0.10.0
==========

:data: 2020-03-25

Features
--------

* Change bundle Reveal.js (3.8.0 -> 3.9.1)
* Add support version (3.8, author's default)

Fixes
-----

* In development, depend by ``sphinxcontrib-gtagjs``. (use in demo)

Extra
-----

* Change license (MIT -> Apache-2.0)
* Use poetry as build environment

ver 0.9.0
=========

:date: 2019-12-22

Fixes
-----

* google-fonts default options is changed for not to render in template.
* Adjusting templates based by sphinx basic theme. (short breaking)

  * Enable ``metatags`` , ``scripts`` and more template values.

ver 0.8.0
=========

:date: 2019-11-11

Features
--------

* Add new config option ``google_font`` to set google-font style.

ver 0.7.0
=========

:date: 2019-10-28

Features
--------

* Add new directive ``revealjs_fragments`` to use Fragment.

ver 0.6.1
=========

:date: 2019-09-12

Fixes
-----

* Remove tag that refer source not exits

ver 0.6.0
=========

:date: 2019-07-31

Features
--------

* Add new directive ``revealjs_break`` to split sections.

  * Updated demo

Extra
-----

* Add docstrings any sources. (ignore tests)
* Remove Pipenv.
* Migrate metadata and options from ``setup.py`` into ``setup.cfg`` .
* Use bumpversion for versioning

ver 0.5.1
=========

:date: 2019-06-30

Extra
-----

* Update Reveal.js from 3.7.0 to 3.8.0


ver 0.5.0
=========

:date: 2018-12-31

Features
--------

* Revealjs initialize config accept from sphinx document config
* Revealjs initialize config accept from ``revealjs_slide`` directive


ver 0.4.1
=========

:date: 2018-12-21

Fixes
-----

* ``revealjs_section`` directive of source apply for itself only

ver 0.4.0
=========

:date: 2018-12-10

Features
--------

* It can select theme per presentations.


ver 0.3.1
=========

First public release on PyPI.
