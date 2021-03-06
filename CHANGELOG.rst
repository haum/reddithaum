Change Log
==========

All notable changes to this project will be documented in this file.
This project adheres to `Semantic Versioning <http://semver.org/>`__.

[Unreleased]
------------

[2.1] - 2015-08-15
------------------

- Using ``hms_base`` version 2

[2.0] - 2015-06-24
------------------

- Using package ``hms_base`` instead of copying its source code
- Using ``setup.py`` packaging for easier installation, dependency management
  and use
- Moving from an IRC bot to a microservice over RabbitMQ
- Handling reddit downtimes

[1.0] - 2015-12-24
------------------

Added
~~~~~

- Display name of submitter on IRC

Changed
~~~~~~~

- Using Python 3 instead of Python 2.
- Using Python's ``logging`` library instead of custom MessageLog
   class.

Removed
~~~~~~~

- Display of post id on IRC

[0.2] - 2015-12-24
------------------

Added
~~~~~

- MIT License and other literature (AUTHORS file, this CHANGELOG, …)

Changed
~~~~~~~

- Project literature is now in English instead of French.

[0.1] - 2015-12-22
------------------

Added
~~~~~

- Basic implementation in Python 2 using Twisted.
