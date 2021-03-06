============================
besluitregistratiecomponent
============================

:Version: 0.1.0
:Source: https://github.com/VNG-Realisatie/gemma-besluitregistratiecomponent
:Keywords: zaken, zaakgericht werken, GEMMA, RGBZ, BRC
:PythonVersion: 3.6

|build-status|

Referentieimplementatie van de besluitregistratiecomponent (BRC).

Introduction
============

Binnen het Nederlandse gemeentelandschap wordt zaakgericht werken nagestreefd.
Om dit mogelijk te maken is er gegevensuitwisseling nodig. Er is een behoefte
om informatieobjecten (documenten) te relateren aan zaken.

Deze referentieimplementatie toont aan dat de API specificatie voor de
besluitregistratiecomponent (hierna BRC) implementeerbaar is, en vormt een
voorbeeld voor andere implementaties indien ergens twijfel bestaat.

Deze component heeft ook een `testomgeving`_ waar leveranciers tegenaan kunnen
testen.

Documentation
=============

See ``docs/contents/installation`` for installation instructions, available settings and
commands.

If you intend to develop on the component, we recommend the ``development.rst``
document, otherwise ``docker.rst`` is recommended.


References
==========

* `Issues <https://github.com/VNG-Realisatie/gemma-besluitregistratiecomponent/issues>`_
* `Code <https://github.com/VNG-Realisatie/gemma-besluitregistratiecomponent/>`_


.. |build-status| image:: http://jenkins.nlx.io/buildStatus/icon?job=gemma-besluitregistratiecomponent-stable
    :alt: Build status
    :target: http://jenkins.nlx.io/job/gemma-besluitregistratiecomponent-stable

.. |requirements| image:: https://requires.io/github/VNG-Realisatie/gemma-besluitregistratiecomponent/requirements.svg?branch=master
     :target: https://requires.io/github/VNG-Realisatie/gemma-besluitregistratiecomponent/requirements/?branch=master
     :alt: Requirements status

.. _testomgeving: https://ref.tst.vng.cloud/brc/
