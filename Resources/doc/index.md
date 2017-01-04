**❮ NOTE ❯** This bundle releases new versions on a regular basis. Make sure
to update your dependencies frequently to get the latest version.
[Check out the changelog](https://github.com/javiereguiluz/EasyAdminBundle/releases)
to learn about the new features and read the [UPGRADE guide](https://github.com/javiereguiluz/EasyAdminBundle/blob/master/UPGRADE.md).

-----

EasyAdmin
=========

[![Build Status](https://travis-ci.org/javiereguiluz/EasyAdminBundle.svg?branch=master)](https://travis-ci.org/javiereguiluz/EasyAdminBundle)
[![SensioLabsInsight](https://insight.sensiolabs.com/projects/a3bfb8d9-7b2d-47ab-a95f-382af395bd51/mini.png)](https://insight.sensiolabs.com/projects/a3bfb8d9-7b2d-47ab-a95f-382af395bd51)
[![Coverage Status](https://coveralls.io/repos/javiereguiluz/EasyAdminBundle/badge.svg?branch=master)](https://coveralls.io/r/javiereguiluz/EasyAdminBundle?branch=master)
[![Symfony](https://img.shields.io/badge/Symfony-%202.x%20and%203.x-green.svg "Supports Symfony 2.x and 3.x")](https://symfony.com/)

<img src="images/easyadmin-promo.png" alt="Symfony Backends created with EasyAdmin" align="right" />

EasyAdmin lets you create administration backends for Symfony applications
with unprecedented simplicity.

**Features**

  * **CRUD** operations on Doctrine entities (create, edit, list, delete).
  * Full-text **search**, **pagination** and column **sorting**.
  * Fully **responsive** design (smartphones, tablets and desktops).
  * Supports Symfony 2.x and 3.x.
  * Translated into tens of languages.
  * **Fast**, **simple** and **smart** where appropriate.

**Requirements**

  * Symfony 2.3+ or 3.x applications (Silex not supported).
  * Doctrine ORM entities (Doctrine ODM and Propel not supported).
  * Entities with composite keys or using inheritance are not supported.

Documentation
-------------

#### Getting Started Guide

The [Getting Started Guide](getting-started.md) explains how to
install the bundle and how to create your first backend. This guide is a must-
read before using EasyAdmin.

#### The Book

  * [Chapter 1 - Basic configuration](book/1-basic-configuration.md)
  * [Chapter 2 - Design configuration](book/2-design-configuration.md)
  * [Chapter 3 - `list`, `search` and `show` views configuration](book/3-list-search-show-configuration.md)
  * [Chapter 4 - `edit` and `new` views configuration](book/4-edit-new-configuration.md)
  * [Chapter 5 - Actions configuration](book/5-actions-configuration.md)
  * [Chapter 6 - Menu configuration](book/6-menu-configuration.md)
  * [Chapter 7 - Creating complex and dynamic backends](book/7-complex-dynamic-backends.md)
  * [Chapter 8 - About this project](book/8-about.md)
  * [Appendix - Full configuration reference](book/configuration-reference.md)

#### Tutorials

  * [How to translate the backend](tutorials/i18n.md)
  * [How to define custom actions](tutorials/custom-actions.md)
  * [How to define custom options for entity properties](tutorials/custom-property-options.md)
  * [How to manage configuration for complex backends](tutorials/complex-backend-config.md)
  * [Tips and tricks](tutorials/tips-and-tricks.md)

#### Third-party bundles/services integrations

  * [How to upload files and images with VichUploaderBundle](tutorials/upload-files-and-images.md)
  * [How to integrate FOSUserBundle to manage users](tutorials/fosuserbundle-integration.md)
  * [How to use a WYSIWYG editor with IvoryCKEditorBundle](tutorials/wysiwyg-editor.md)
  * [How To integrate FOSRestBundle and EasyAdmin](tutorials/fosrestbundle-integration.md)

> **❮ NOTE ❯** you are reading the documentation of the bundle's **development**
> version. You can also [read the documentation of the latest stable version ➜]
> (https://github.com/javiereguiluz/EasyAdminBundle/tree/v1.16.3/).

Demo Application
----------------

[easy-admin-demo](https://github.com/javiereguiluz/easy-admin-demo) is a complete
Symfony application created to showcase EasyAdmin features.

License
-------

This software is published under the [MIT License](LICENSE.md)
