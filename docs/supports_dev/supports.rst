
.. _support-and-optim:


***************************
Software & References
***************************

.. contents:: Table of Contents
   :local:

-------

Software
=========================

Graphene Core
----------------------

.. list-table::
   :widths: 15 80
   :header-rows: 0

   * - `Graphene Core <https://github.com/graphene-blockchain/graphene-core>`_
     - Graphene Core is the Graphene blockchain implementation and command-line interface
   * - `Docker Container <https://github.com/graphene-blockchain/graphene-core/blob/master/README-docker.md>`_
     - Built-in Dockerfile to support docker containers.

|

Graphene Core C++ Library
---------------------------

.. list-table::
   :widths: 15 80
   :header-rows: 0

   * - `Graphene FC <https://github.com/graphene-blockchain/graphene-fc>`_
     - Fast-compiling C++ library  provides a set of utility libraries useful for the development of asynchronous libraries
   * - `Websocket pp <https://github.com/bitshares/websocketpp>`_
     - C++ websocket client/server library

|

HTLC
----------------------

.. list-table::
   :widths: 15 80
   :header-rows: 0

   * - `Hashed Time-Lock Contracts (HTLC) on Graphene <https://github.com/graphene-blockchain/graphene-core/wiki/HTLC>`_
     - TESTNET: User Guide for Hashed Time-Lock Contracts (HTLC) on Graphene
   * - `Hashed Time-Lock Contracts (HTLC) on Graphene:CN <https://github.com/graphene-blockchain/graphene-core/wiki/HTLC-(CN)>`_
     - 测试网：Graphene 哈希时间锁合约（HTLC）用户指南


|

API Related
----------------------

.. list-table::
   :widths: 15 80
   :header-rows: 0

   * - `Graphene Explorer API <https://github.com/graphene-blockchain/graphene-explorer-api>`_
     - REST API for Graphene


|

Python
----------------------

.. list-table::
   :widths: 15 80
   :header-rows: 0

   * - `Python Graphene <https://github.com/bitshares/python-bitshares>`_
     - Fully featured client-side library for the Graphene Blockchain - written entirely in python.
   * - `uptick <https://github.com/bitshares/uptick>`_
     - Python-based CLI tool set for Graphene blockchain
   * - `Faucet - Tapin <https://github.com/xeroc/tapin>`_
     -  Tapin is a python-based faucet for Graphene-based blockchains (e.g. Graphene).


|

JavaScript
----------------------

.. list-table::
   :widths: 15 80
   :header-rows: 0

   * - `Graphene JS <https://github.com/bitshares/bitsharesjs>`_
     - JavaScript tools for Graphene Encryption and Serialization. https://bitsharesjs.bitshares.org/
   * - `Graphene JS-WS <https://github.com/bitshares/bitsharesjs-ws>`_
     - JavaScript websocket interface for Graphene

|

Graphene UI
----------------------

.. list-table::
   :widths: 15 80
   :header-rows: 0

   * - `Graphene UI <https://github.com/graphene-blockchain/graphene-ui>`_
     - Graphical User Interface for Graphene
   * - `Graphene UI API <https://github.com/graphene-blockchain/graphene-ui-api>`_
     - RESTful API server for Graphene based on express-es6-rest-api
   * - `develop.bitshares.org <https://github.com/bitshares/develop.bitshares.org>`_
     - Bleeding edge hosted wallet off the develop branch of bitshares-ui
   * - `reconnecting-websocket <https://github.com/bitshares/reconnecting-websocket>`_
     - A small decorator for the JavaScript WebSocket API that automatically reconnects
|

Mobile
----------------------

.. list-table::
   :widths: 15 80
   :header-rows: 0

   * - `Graphene Mobile App <https://github.com/graphene-blockchain/graphene-mobile-app>`_
     - This is the mobile app for bitshares blockchain

|

Other Related Software
----------------------

.. list-table::
   :widths: 15 80
   :header-rows: 0

   * - `G-Wallet <https://github.com/bitshares/gwallet>`_
     - G-Wallet is a Graphene desktop(Linux, Windows, MAC) wallet program written in C++ using wxWidgets.
   * - `beet <https://github.com/bitshares/beet>`_
     -  Beet is a stand-alone key/identity-manager and signing app for Graphene, heavily influenced by Scatter
   * - `faucet <https://github.com/bitshares/faucet>`_
     -
   * - `secp256k1-zkp <https://github.com/bitshares/secp256k1-zkp>`_
     - Experimental fork of libsecp256k1 with support for pedersen commitments and range proofs
   * - `btsgo <https://github.com/bitshares/btsgo>`_
     -


|


--------

References
=========================

Graphene Core
--------------------

* `Graphene Core: Doxygen Document <https://open-explorer.io/doxygen/fc/>`_

* `BSIPs <https://github.com/bitshares/bsips>`_  - Graphene Improvement Proposals and Protocols

* `Graphene FC: Doxygen Document <https://open-explorer.io/doxygen/fc/>`_

|

API Related
----------------------

* :ref:`explorer-wrappers`

  - For Mainnet and Tesenet: ES Wrapper to query the Graphene data. *Try it out!*
  - Check the Graphene blockchain health.

* `Graphene Explorer REST API - Installation Guide <https://github.com/oxarbitrage/bitshares-explorer-api#bitshares-explorer-rest-api>`_

  - Step by step on everything needed to have your own Graphene Explorer API up and running for a production environment.

|

Plugins
----------------------

* `Graphene Plugins List: Github ReadMe <https://github.com/graphene-blockchain/graphene-core/blob/master/libraries/plugins/README.md>`_

  - ``account_history``, ``debug_witness``, ``delayed_node``, ``elasticsearch``, ``es_objects``,  ``grouped_orders``, ``market_history``, ``snapshot``, ``witness``


|


Testing Tool(s)
----------------------

* :ref:`what-if-test`

  - The debug_node is a tool to allow developers to run many interesting sorts of "what-if" tests using state from a production blockchain.

|

Python
----------------------

* `Python Graphene Documentation <http://docs.pybitshares.com/en/latest/>`_

* :ref:`how-to-setup-python-lib` (also, How to Create MPAs/UIAs with Python)

* :ref:`monitor-account-python` - (How to setup)

* :ref:`websocket-script-support`  - (websocket-client interact with the Core API)

|

JavaScript
----------------------

* :ref:`monitor-balance-nodejs`

  - This nodejs script monitors the balance history of an account in a graphene-based network


|