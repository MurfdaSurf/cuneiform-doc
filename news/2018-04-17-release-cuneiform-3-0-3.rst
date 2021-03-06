Release Cuneiform 3.0.3
=======================

2018-04-17

I have released `Cuneiform 3.0.3 <https://github.com/joergen7/cuneiform/releases/tag/3.0.3>`_. This release introduces a web-server hosted by the CRE that provides status information and a history of all foreign function applications. Moreover, it adds Erlang and Java foreign language support.

Compatibility
-------------

* We seize support for OTP-18.x. From now on, Cuneiform releases are compatible to OTP-19.0 upward.

Foreign Language Support
------------------------

* Erlang foreign language support added.
* Java foreign language support added.

Execution Environment
---------------------

* The CRE now serves status information and history information in a web-interface. It is reachable under port `4142` on the machine hosting the CRE. The web-server supports the `GET` methods for the resources `/status.json` and `cache.json`.