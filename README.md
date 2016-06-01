Parallax Template
=================

This is a basic template set for Phire CMS 2 to demonstrate using the
phire-templates module. It is built using Bootstrap and Font Awesome.

OVERVIEW
========

A template or template sets are meant to be used with the phire-templates
module. They allow for a reusable set of string templates to be stored and
managed in the database via the system. Those templates can be applied to
content for layout purposes.

INSTALLATION & USE
==================

Typically, you can save your string templates directly into the system in the
templates area. They then become available to content types if you set them
to "visible." Additionally, you can upload a template set, like in this repo,
and it will install the set of templates for you and make them available for use.

Templates work by using placeholders to display values in them, for example:

* [{title}]
* [{description}]
* [{content}]

For a more in-depth look at how to display content in templates, take a look at the
documentation for pop-view, the component that it is built on:

http://docs.popphp.org/en/latest/user_guide/views.html#stream-syntax
