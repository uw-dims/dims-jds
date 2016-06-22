.. _frontend:

================================
Front End (User Interfaces, CLI)
================================

There are two primary ways of accessing DIMS functionality: a *web based application* for
a graphical interface, and *command line programs* that can be invoked from a command line
or scripts.

Web application
---------------

The web application consists of a front end client application which runs
in a browser and a back end server application that receives requests from
the client and communicates with other DIMS programs, services and 
components.

Web application client
~~~~~~~~~~~~~~~~~~~~~~

The web application client is a Javascript AngularJS application. The
following skills at an intermediate to advanced level are required:

+ Javascript 
+ AngularJS
+ CSS, Less
+ Bootstrap
+ Promises ($q library)
+ AngularJS and Javascript unit and end-to-end testing with Karma, Mocha, 
  Chai, Jasmine, Protractor, among others
+ Automation using Grunt
+ Package management using npm, Bower
+ JSON Web Tokens

In addition, the developer should be familiar with Javascript
functional programming, general principles of web 2.0 architectures and 
practices.

Web application server
~~~~~~~~~~~~~~~~~~~~~~

The backend server for the web application is written in Node.js and Express. 
The following skills at an intermediate to advanced level are required when 
working on the web application server:

+ Javascript 
+ Node.js 
+ Express
+ Promises (Q library- https://github.com/kriskowal/q)
+ Testing using Karma, Mocha, Chai, Sinon
+ Automation using Grunt
+ Package management using npm
+ JSON Web Tokens

In addition, the developer must be familiar with Javascript functional 
programming, RabbitMQ (AMQP), socket.io,
Redis, Postgres.

Command line front end
----------------------

+ Java command line programs
+ Python 2.7 command line programs
    + OpenStack's `cliff - Command Line Interface Formulation Framework`_ (GitHub `openstack/cliff`_)

+ Bash command line programs
    + Google's `shFlags`_ module (GitHub `kward/shflags`_)

..

.. _Node.js: http://nodejs.org/
.. _cliff - Command Line Interface Formulation Framework: http://docs.openstack.org/developer/cliff/
.. _openstack/cliff: https://github.com/openstack/cliff
.. _shFlags: https://github.com/kward/shflags/wiki/Documentation12x
.. _kward/shflags: https://github.com/kward/shflags
