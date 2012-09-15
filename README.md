requery
=======

Simple way to store and use querys in database for use of DBA's

Installation
------------

Download and put ``requery`` on your ``PYTHONPATH``

2. Add redis_dashboard to your ``INSTALLED_APPS`` setting::

       INSTALLED_APPS = (
           # ...
           'requery',
       )

3. Run ``python manage.py syncdb``


Please help out
---------------
This project is still under development. Feedback and suggestions are very
welcome and I encourage you to use the [Issues
list](http://github.com/ebertti/requery/issues) on Github to provide that
feedback.

Feel free to fork this repo and to commit your additions. For a list of all
contributors, please see the [AUTHORS](AUTHORS) file.


This file was created by PyCharm 2.6.1 for binding GitHub repository