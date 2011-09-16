HubText
=======

This is an example app to interface Twilio with Hubspot lead database to send text messages to leads.

To install this app (assuming you are on Mac or Linux)::

    $ sudo easy_install pip
    $ sudo pip install virtualenv
    $ virtualenv hubtext
    $ cd hubtext
    $ source bin/activate
    (hubtext)$ git clone git@github.com:natea/hubtext.git
    (hubtext)$ cd hubtext
    (hubtext)$ pip install -r requirements.txt
    (hubtext)$ python manage.py syncdb
    (hubtext)$ python manage.py runserver
    
Resources
=========

Hubspot docs
------------

* `Hubspot Dev wiki <http://docs.hubapi.com/>`_
* `Performable Webhook API <http://help2.hubspot.com/display/DOC/Webhook+API>`_

Django packages
---------------

* `django-twilio <https://github.com/rdegges/django-twilio>`_  
* `django-twilio docs <http://django-twilio.readthedocs.org/en/latest/>`_
* `tastypie <https://github.com/toastdriven/django-tastypie>`_
* `tastypie docs <http://django-tastypie.readthedocs.org/en/latest/>`_