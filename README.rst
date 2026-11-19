=======
README
=======

Sunbeam Specifications
======================


This git repository is used to hold approved design specifications for additions
to the Sunbeam project. Reviews of the specs are done in gerrit, using a similar
workflow to how we review and merge changes to the code itself. For specific
policies around specification review, refer to the end of this document.

The layout of this repository is::

  specs/<release>/

Where there are two sub-directories:

  specs/<release>/approved: specifications approved but not yet implemented
  specs/<release>/implemented: implemented specifications

Example specifications
----------------------

You can find an example spec in ``specs/template.rst``.

License
-------

The specification documents in this repository are licensed under the
Creative Commons Attribution 3.0 Unported License; see the ``LICENSE``
file. The supporting code, such as ``tests/`` and ``doc/source/*.py``,
is licensed under the Apache License, Version 2.0, as stated in each
file's header.
