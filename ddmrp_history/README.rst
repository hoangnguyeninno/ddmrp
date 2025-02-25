=============
DDMRP History
=============

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:d037b8db306d50283d8a06fa845eaf84e37523c62ea94cc5ccd570c64158fe52
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-LGPL--3-blue.png
    :target: http://www.gnu.org/licenses/lgpl-3.0-standalone.html
    :alt: License: LGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fddmrp-lightgray.png?logo=github
    :target: https://github.com/OCA/ddmrp/tree/16.0/ddmrp_history
    :alt: OCA/ddmrp
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/ddmrp-16-0/ddmrp-16-0-ddmrp_history
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/ddmrp&target_branch=16.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

Allow to extend DDMRP App to store historical data of buffers.

**Table of contents**

.. contents::
   :local:

Installation
============

You need to install the python pandas library::

    pip install pandas==0.25.3

Usage
=====

You can access, as a inventory manager, to all the DDMRP historical data
throught *Inventory > Reports > DDMRP Buffer History*. Additionally you can
see a historical evolution chart of any buffer at the bottom of its form view,
either by a planning or a execution perspective.

Changelog
=========

13.0.1.0.0 (2020-06-16)
~~~~~~~~~~~~~~~~~~~~~~~

* Migration to v13.

11.0.1.0.1 (2019-02-07)
~~~~~~~~~~~~~~~~~~~~~~~

* Make history charts responsive and remove NFP from execution chart.
* Use user's language to format dates in the charts.

11.0.1.0.0 (2018-08-01)
~~~~~~~~~~~~~~~~~~~~~~~

* Start of the history

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/ddmrp/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/ddmrp/issues/new?body=module:%20ddmrp_history%0Aversion:%2016.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* ForgeFlow

Contributors
~~~~~~~~~~~~

* Lois Rilo <lois.rilo@forgeflow.com>
* Jordi Ballester <jordi.ballester@forgeflow.com>
* Akim Juillerat <akim.juillerat@camptocamp.com>
* Christopher Ormaza <chris.ormaza@forgeflow.com>

Other credits
~~~~~~~~~~~~~

The initial development of this module has been financially supported by:

* Aleph Objects, Inc.

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

.. |maintainer-JordiBForgeFlow| image:: https://github.com/JordiBForgeFlow.png?size=40px
    :target: https://github.com/JordiBForgeFlow
    :alt: JordiBForgeFlow
.. |maintainer-LoisRForgeFlow| image:: https://github.com/LoisRForgeFlow.png?size=40px
    :target: https://github.com/LoisRForgeFlow
    :alt: LoisRForgeFlow

Current `maintainers <https://odoo-community.org/page/maintainer-role>`__:

|maintainer-JordiBForgeFlow| |maintainer-LoisRForgeFlow| 

This module is part of the `OCA/ddmrp <https://github.com/OCA/ddmrp/tree/16.0/ddmrp_history>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
