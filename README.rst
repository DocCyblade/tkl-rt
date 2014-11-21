RT: Request Tracker 
=============================

RT is a battle-tested issue tracking system which thousands of
organizations use for bug tracking, help desk ticketing, 
customer service, workflow processes, change management, network 
operations, youth counselling and even more.


This appliance includes all the standard features in `TurnKey LAPP`:

- SSL support out of the box.
- PHP, Python and Perl support for Apache2 and PostgreSQL.
- `PHPPgAdmin`_ administration frontend for PostgreSQL (listening on
  port 12322 - uses SSL).
- Webmin modules for configuring Apache2, PHP and PostgreSQL.
- PostgreSQL listening on localhost (security)
- PostgreSQL password encryption enabled by default (security).
- The *postgres* user is trusted when connecting over local unix sockets
  (convenience).

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH: username **root**
-  PostgreSQL, phpPgAdmin: username **postgres**

.. _TurnKey LAPP: http://www.turnkeylinux.org/lapp
