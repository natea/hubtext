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
    
To run the tests::

    $ python manage.py test
    
Resources
=========

Hubspot docs
------------

* `Hubspot Dev wiki <http://docs.hubapi.com/>`_
* `Performable Webhook API <http://help2.hubspot.com/display/DOC/Webhook+API>`_

Packages
--------

* `twilio-python <http://readthedocs.org/docs/twilio-python/en/latest/>`_
* `Sending text messages with Twilio <http://readthedocs.org/docs/twilio-python/en/latest/usage/messages.html>`_
* `django-twilio <https://github.com/rdegges/django-twilio>`_  
* `django-twilio docs <http://django-twilio.readthedocs.org/en/latest/>`_
* `tastypie <https://github.com/toastdriven/django-tastypie>`_
* `tastypie docs <http://django-tastypie.readthedocs.org/en/latest/>`_

Examples
--------

* `django-door <https://github.com/sunlightlabs/door-django/>`_ integrating Django with Twilio

Custom Webhook Info
___________________

* `Post Bin Output <http://www.postbin.org/100el3i>`_
* `Event API <http://analytics.performable.com/v1/event?_n=3MjmQk5zKfkP&_a=8LuYZb>`_
