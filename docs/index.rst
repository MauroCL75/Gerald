.. Gerald documentation master file, created by
   sphinx-quickstart on Mon Jun  7 17:57:39 2010.

========================
Gerald the half a schema
========================

Note that as of January 2017 this project is no longer under active development. 

A Python Schema Comparison Tool
===============================

Gerald is a general purpose database schema toolkit written in Python_. It can be used for cataloguing, managing and deploying database schemas. It is designed to allow you to easily identify the differences between databases.

You can use Gerald to determine the differences between your development and test environments, or to integrate changes from a number of different developers into your integration database.

You can use Gerald to compare schemas across different database engines (e.g. Oracle_ and MySQL_), you can also use it to produce database agnostic documentation in text or XML.

Gerald is designed from the ground up to support as many popular relational database systems as possible.  
Currently it will document and compare schemas from databases implemented in MySQL_, Oracle_ and PostgreSQL_.
Other databases will be supported in future releases.

You can download Gerald at the `package page`_

Contents
========

.. toctree::
   :maxdepth: 1

   user_guide
   schema_api
   add_another_database
   contributing
   distributing

Links
=====

Everything you need to get and run Gerald is at these links;

- Download the package from the PyPI_ `package page`_
- Look at the :doc:`API <schema_api>` that is used throughout the code
- The project issue tracker and source code are in the `code repository`_ courtesy of BitBucket_. Check out a copy with;

::

    hg clone https://bitbucket.org/andy47/gerald

Future Plans 
============

This is release 0.4.1.1 of Gerald. It's still alpha code, but I use it all of the time.
Having said that, I'm fairly happy with the current functionality so I will only change it if I absolutely have to, and then usually to extend the features available.
This is a minor release with a few bug fixes, improvements and tidying up of the code. It fixes a number of bugs. The main purpose of this release is to fix the installation process when using ``easy_install``. Full details can be found in the CHANGELOG.txt file provided with the code.

The core function is fairly solid and will support a number of enhancements.
I'm specifically thinking about, but in no particular order;

- Improvements to the comparison algorithms
- `SQL Server`_ support
- SQLite_ support
- Firebird_ support
- `DB2 UDB`_ support
- A proper persistence mechanism for schema models
- Make columns first class objects
- Support the input, storage and retrieval of notes against any object
- A diagramming front end

If anyone has suggestions I'm happy to hear your thoughts. Send an email to `andy47@halfcooked.com <mailto:andy47@halfcooked.com>`_

Outstanding feature requests and bugs are recorded on the `project issues`_ page at BitBucket_

Indices and tables
==================

* :ref:`genindex`
* :ref:`search`

.. * :ref:`modindex`

----

:Author: `Andy Todd <andy47@halfcooked.com>`_
:Last Updated: Wednesday the 18th of January, 2017.

.. _Python: http://www.python.org/
.. _Agile: http://www.agiledata.org/
.. _MySQL: http://www.mysql.com/
.. _Oracle: http://www.oracle.com/
.. _PostgreSQL: http://www.postgresql.org/
.. _SQLite: http://www.sqlite.org/
.. _`SQL Server`: http://www.microsoft.com/
.. _`DB2 UDB`: http://www.ibm.com/software/data/DB2/
.. _Firebird: http://www.firebirdsql.org/
.. _PyPI: http://pypi.python.org/pypi/
.. _`package page`: http://pypi.python.org/pypi/gerald/
.. _BitBucket: https://bitbucket.org
.. _`code repository`: https://bitbucket.org/andy47/gerald/src
.. _`project issues`: https://bitbucket.org/andy47/gerald/issues?status=new&status=open
.. _`download page`: https://bitbucket.org/andy47/gerald/downloads
.. _Sphinx: http://sphinx.pocoo.org/
