.. image:: https://github.com/Star2Billing/cdr-stats/raw/master/docs/source/_static/images/cdr-stats_600.png

CDR-Stats is a free and open source call detail record analysis and reporting software for Freeswitch, 
Asterisk and other types of VoIP Switch. It allows you to interrogate CDR to provide reports 
and statistics via a simple to use powerful web interface.

It is based on the Django Python Framework, Celery, SocketIO, Gevent and MongoDB.

   

Documentation
-------------

Documentation can be found :

    - http://www.cdr-stats.org/documentation

Beginner's Guide :

    - http://www.newfies-dialer.org/documentation/beginners-guide/


Beginner's Guide :

    - http://www.newfies-dialer.org/pdf/Newfies.pdf


Applications
------------

* User UI :
    http://localhost:8008/
    This application provide Reports, CDR Viewing, CDR reporting, Dashboard.
    Users can login and see their CDR only.

.. image:: https://github.com/Star2Billing/cdr-stats/raw/master/screenshot/cdr-stats-user.png

* Admin UI :
    http://localhost:8008/admin/
    This interface provides user (ACL) management, assignation of accountcode, 
    also basic CRUD functions on the CDR

.. image:: https://github.com/Star2Billing/cdr-stats/raw/master/screenshot/cdr-stats-admin.png


Additional information
-----------------------

Fork the project on GitHub : https://github.com/Star2Billing/cdr-stats

License : MPL 2.0 (https://raw.github.com/Star2Billing/cdr-stats/master/COPYING)

Website : http://www.cdr-stats.org


Support 
-------

Star2Billing S.L. (http://www.star2billing.com) offers consultancy including 
installation, training and customization 

Please email us at cdr-stats@star2billing.com for more information
