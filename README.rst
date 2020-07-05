====
subnet
====

|nimble-version| |nimble-install| |gh-actions|

``subnet`` prints subnet mask.

.. contents:: Table of contents

Usage
=====

.. code-block:: shell

   $ subnet 100.100.200.1/24
   100.100.200.1        24      01100100011001001100100000000001        11111111111111111111111100000000

   $ subnet -Hc 100.100.200.1/24
   IPAddr       CIDR    Bin     Mask
   100.100.200.1        24      01100100011001001100100000000001        11111111111111111111111100000000

   $ subnet 0-32.100.200.1/24
   $ subnet -32.100.200.1/24
   $ subnet 64-.100.200.1/24
   $ subnet 128-.100.200.1/24
   $ subnet 100.100.200.0,8,16,24/24

Installation
============

.. code-block:: shell

   $ nimble install -Y subnet

LICENSE
=======

MIT

.. |gh-actions| image:: https://github.com/jiro4989/subnet/workflows/build/badge.svg
   :target: https://github.com/jiro4989/subnet/actions
.. |nimble-version| image:: https://nimble.directory/ci/badges/subnet/version.svg
   :target: https://nimble.directory/ci/badges/subnet/nimdevel/output.html
.. |nimble-install| image:: https://nimble.directory/ci/badges/subnet/nimdevel/status.svg
   :target: https://nimble.directory/ci/badges/subnet/nimdevel/output.html
