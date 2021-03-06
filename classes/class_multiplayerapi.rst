.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the MultiplayerAPI.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_MultiplayerAPI:

MultiplayerAPI
==============

**Inherits:** :ref:`Reference<class_reference>` **<** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------



Member Functions
----------------

+------------------------------------------+--------------------------------------------------------------------------------------------------------+
| void                                     | :ref:`add_peer<class_MultiplayerAPI_add_peer>` **(** :ref:`int<class_int>` id **)**                    |
+------------------------------------------+--------------------------------------------------------------------------------------------------------+
| void                                     | :ref:`clear<class_MultiplayerAPI_clear>` **(** **)**                                                   |
+------------------------------------------+--------------------------------------------------------------------------------------------------------+
| void                                     | :ref:`connected_to_server<class_MultiplayerAPI_connected_to_server>` **(** **)**                       |
+------------------------------------------+--------------------------------------------------------------------------------------------------------+
| void                                     | :ref:`connection_failed<class_MultiplayerAPI_connection_failed>` **(** **)**                           |
+------------------------------------------+--------------------------------------------------------------------------------------------------------+
| void                                     | :ref:`del_peer<class_MultiplayerAPI_del_peer>` **(** :ref:`int<class_int>` id **)**                    |
+------------------------------------------+--------------------------------------------------------------------------------------------------------+
| :ref:`PoolIntArray<class_poolintarray>`  | :ref:`get_network_connected_peers<class_MultiplayerAPI_get_network_connected_peers>` **(** **)** const |
+------------------------------------------+--------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                    | :ref:`get_network_unique_id<class_MultiplayerAPI_get_network_unique_id>` **(** **)** const             |
+------------------------------------------+--------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                    | :ref:`get_rpc_sender_id<class_MultiplayerAPI_get_rpc_sender_id>` **(** **)** const                     |
+------------------------------------------+--------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                  | :ref:`has_network_peer<class_MultiplayerAPI_has_network_peer>` **(** **)** const                       |
+------------------------------------------+--------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                  | :ref:`is_network_server<class_MultiplayerAPI_is_network_server>` **(** **)** const                     |
+------------------------------------------+--------------------------------------------------------------------------------------------------------+
| void                                     | :ref:`poll<class_MultiplayerAPI_poll>` **(** **)**                                                     |
+------------------------------------------+--------------------------------------------------------------------------------------------------------+
| void                                     | :ref:`server_disconnected<class_MultiplayerAPI_server_disconnected>` **(** **)**                       |
+------------------------------------------+--------------------------------------------------------------------------------------------------------+
| void                                     | :ref:`set_root_node<class_MultiplayerAPI_set_root_node>` **(** :ref:`Node<class_node>` node **)**      |
+------------------------------------------+--------------------------------------------------------------------------------------------------------+

Signals
-------

.. _class_MultiplayerAPI_connected_to_server:

- **connected_to_server** **(** **)**

.. _class_MultiplayerAPI_connection_failed:

- **connection_failed** **(** **)**

.. _class_MultiplayerAPI_network_peer_connected:

- **network_peer_connected** **(** :ref:`int<class_int>` id **)**

.. _class_MultiplayerAPI_network_peer_disconnected:

- **network_peer_disconnected** **(** :ref:`int<class_int>` id **)**

.. _class_MultiplayerAPI_server_disconnected:

- **server_disconnected** **(** **)**


Member Variables
----------------

  .. _class_MultiplayerAPI_network_peer:

- :ref:`NetworkedMultiplayerPeer<class_networkedmultiplayerpeer>` **network_peer**

  .. _class_MultiplayerAPI_refuse_new_network_connections:

- :ref:`bool<class_bool>` **refuse_new_network_connections**


Member Function Description
---------------------------

.. _class_MultiplayerAPI_add_peer:

- void **add_peer** **(** :ref:`int<class_int>` id **)**

.. _class_MultiplayerAPI_clear:

- void **clear** **(** **)**

.. _class_MultiplayerAPI_connected_to_server:

- void **connected_to_server** **(** **)**

.. _class_MultiplayerAPI_connection_failed:

- void **connection_failed** **(** **)**

.. _class_MultiplayerAPI_del_peer:

- void **del_peer** **(** :ref:`int<class_int>` id **)**

.. _class_MultiplayerAPI_get_network_connected_peers:

- :ref:`PoolIntArray<class_poolintarray>` **get_network_connected_peers** **(** **)** const

.. _class_MultiplayerAPI_get_network_unique_id:

- :ref:`int<class_int>` **get_network_unique_id** **(** **)** const

.. _class_MultiplayerAPI_get_rpc_sender_id:

- :ref:`int<class_int>` **get_rpc_sender_id** **(** **)** const

.. _class_MultiplayerAPI_has_network_peer:

- :ref:`bool<class_bool>` **has_network_peer** **(** **)** const

.. _class_MultiplayerAPI_is_network_server:

- :ref:`bool<class_bool>` **is_network_server** **(** **)** const

.. _class_MultiplayerAPI_poll:

- void **poll** **(** **)**

.. _class_MultiplayerAPI_server_disconnected:

- void **server_disconnected** **(** **)**

.. _class_MultiplayerAPI_set_root_node:

- void **set_root_node** **(** :ref:`Node<class_node>` node **)**


