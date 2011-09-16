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
    
