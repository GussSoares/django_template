django_template
=======================

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

**django_template** is my skeleton for Django projects. It provides a
directory structure for Django projects during development and deployment.


Meta
----

Author:
    Gustavo

Contributors:
    This template is an adaptation of an original project by: [agirardeaudale], [jmrbcu]

Status:
    maintained, in development

Version:
    1.4

Django Version:
    3.0, 2.2, 2.1, 2.0, 1.11


Usage
-----

To use this repository just use the ``template`` option of `django-admin
<https://docs.djangoproject.com/en/2.2/ref/django-admin/#startproject>`_::

    $ django-admin startproject --template=https://github.com/gustavo5855/django_template/archive/master.zip [projectname]

If you wish to automagically fill the ``apache2_vhost.sample`` the command is::

    $ django-admin startproject --template=https://github.com/gustavo5855/django_template/archive/master.zip --name apache2_vhost.sample [projectname]


Documentation
-------------

You can see the documentation over at **Read the Docs**: [django-project-skeleton]

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


[agirardeaudale]: <https://github.com/agirardeuadale>
[jmrbcu]: <https://github.com/jmrbcu>
[django-project-skeleton]: <http://django-project-skeleton.readthedocs.org/en/stable/>
