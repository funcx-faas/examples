Globus Compute Examples
--------------
|launch| |docs| |license|

.. |launch| image:: https://mybinder.org/badge_logo.svg
   :target: https://mybinder.org/v2/gh/funcx-faas/examples/HEAD?filepath=notebooks%2FIntroduction.ipynb
   :alt: Launch in Binder
.. |docs| image:: https://readthedocs.org/projects/globus-compute/badge/?version=latest
   :target: https://globus-compute.readthedocs.io/en/latest/
   :alt: Documentation Status
.. |license| image:: https://img.shields.io/badge/License-Apache%202.0-blue.svg
   :target: https://github.com/funcx-faas/examples/blob/master/LICENSE
   :alt: Apache Licence V2.0

Globus Compute is a Function-as-a-Service (FaaS) platform for science that enables
you to register functions in a cloud-hosted service and
then reliably execute those functions on a remote Globus Compute endpoint.
This tutorial is configured to use a tutorial endpoint hosted by the Globus Compute team.
You can setup and use your own endpoint by following
the `Globus Compute documentation. <https://globus-compute.readthedocs.io/en/latest/endpoints.html>`_

Using Globus Compute with Binder
================================

The easiest way to run these tutorials is via Binder. Using Binder you can run the tutorial notebooks in your browser without installing any code locally.

`Start Binder <https://mybinder.org/v2/gh/funcx-faas/examples/HEAD?filepath=notebooks%2FIntroduction.ipynb>`_

Using Globus Compute locally
============================

To install Globus Compute, please ensure you have python3.7+.::

   $ python3 --version

Install using Pip::

   $ pip install globus-compute-sdk

To use our example notebooks you will need Jupyter.::

   $ pip install jupyter


Documentation
=============

Complete documentation for Globus Compute is available `here <https://globus-compute.readthedocs.io>`_