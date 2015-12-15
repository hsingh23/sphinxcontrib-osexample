.. -*- restructuredtext -*-

:author: Sven Strack <sven@so36.net>

==============================
osexample extension for Sphinx
==============================

This is a modified fork of Serge Domkowski's `examplecode extension <https://bitbucket.org/birkenfeld/sphinx-contrib/src/7f39b7f255e34bfe588f0065a5d9709a7d8e7614/examplecode/?at=default>`_ for Sphinx.

About
=====

This is a simple extension that, when rendered as HTML, will fold multiple
code blocks containing different operating systems administration examples into a single block
which can be toggled from one to another using buttons.

It's intended to be used for displaying package manager examples.
(e.g., apt install or dnf install).

This extension adds the ``example-code`` directive which adds a class to
a container wrapping the code blocks that should be folded. The class allows
the included Javascript and CSS to render the folded block and buttons.