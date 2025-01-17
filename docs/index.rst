.. highlight:: bash

.. _index:

============
Installation
============

Security and upgrade notes
==========================

.. WARNING::

    CrateDB versions prior to 4.6.6 are suspicable to the `Log4Shell issue`_
    published on December 12, 2021. Please consider upgrading to the most
    recent version and follow up reading `CrateDB Log4Shell mitigations`_.


Introduction
============

This part of the documentation covers the installation of CrateDB on Linux,
macOS and Windows systems.
The first step to using any software package is getting it properly installed.
Please read this section carefully.

Try CrateDB Cloud
=================

The easiest way to get started with CrateDB is to use a 30 day free CrateDB
Cloud cluster, no credit card requrired. Visit the `sign up page`_ to start your
CrateDB cluster today.

Try CrateDB locally
===================

If you want to try out CrateDB locally on Linux or macOS but would prefer to
avoid the hassle of manual installation or extracting release archives, you can
get a fresh CrateDB node up and running in your current working directory with a
single command:

.. code-block:: console

   sh$ bash -c "$(curl -L https://try.crate.io/)"


.. NOTE::

    This is a quick way to *try out* CrateDB. It is not the recommended method
    to *install* CrateDB in a durable way. The following sections will outline
    that method.


Installing CrateDB
==================

This section of the documentation shows you how to deploy CrateDB in different
environments.

.. rubric:: Table of contents

.. toctree::
   :maxdepth: 3
   :titlesonly:

   basic/index
   linux/index
   containers/index
   cloud/index



.. _CrateDB Log4Shell mitigations: https://community.crate.io/t/security-vulnerability-log4shell-rce-0-day-exploit/935
.. _Log4Shell issue: https://www.lunasec.io/docs/blog/log4j-zero-day/
.. _sign up page: https://crate.io/lp-free-trial
