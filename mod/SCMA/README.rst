===================================================
SCMA codebook input files for the AFF3CT SCMA modem
===================================================

Format
------

**number_of_users** (*V*) **number_of_orthogonal_resources** (*K*) **codebook_size** (*M*)

*KV* rows, *2M* columns 

+------------+------------+-----------+-----------+-----------+
| Re         | Im         | ...       | Re        | Im        |
+------------+------------+-----------+-----------+-----------+
| Re         | Im         | ...       | Re        | Im        |
+------------+------------+-----------+-----------+-----------+
|...         | ...        | ...       | ...       | ...       |
+------------+------------+-----------+-----------+-----------+
| Re         | Im         | ...       | Re        | Im        |
+------------+------------+-----------+-----------+-----------+

Codebook description
--------------------

Codebooks are normalized, that average power of signal will be equal to 1.

+-------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Codebook Set| Description                                                                                                                                                                   |
+=============+===============================================================================================================================================================================+
| **CS1**     | From `1st 5G Algorithm Innovation Competition presentation <http://www.innovateasia.com/5g/images/pdf/1st%205G%20Algorithm%20Innovation%20Competition-ENV1.0%20-%20SCMA.pdf>`_|
+-------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **CS2**     | LDS based on QPSK constellation                                                                                                                                               |
+-------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **CS3**     | Based on `Capacity analysis for non-orthogonal overloading transmissions under constellation constraints <https://ieeexplore.ieee.org/document/7341294>`_                     |
|             | and own optimization for AWGN channel                                                                                                                                         |
+-------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **CS4**     | From `A capacity-based codebook design method for sparse code multiple access systems <https://ieeexplore.ieee.org/document/7752620>`_                                        |
+-------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **CS5**     | From `Signature Design of Sparsely Spread CDMA Based on Superposed Constellation Distance Analysis <https://arxiv.org/abs/1604.04362>`_                                       |
+-------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **CS6**     | From `SCMA Codebooks Optimization Based on Genetic Algorithm <https://ieeexplore.ieee.org/document/8011314>`_                                                                 |
+-------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **CS7**     | From `SCMA Codebooks Optimization Based on Genetic Algorithm <https://ieeexplore.ieee.org/document/8011314>`_                                                                 |
+-------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **CS8**     | From `Iterative multiuser receiver in sparse code multiple access systems <https://ieeexplore.ieee.org/document/7248770>`_, suitable only for uplink fading channel           |
+-------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

The simalation results for **CS1**-**CS7** (AWGN and Reyleigh fading channels) can be find in the paper `SCMA Codebooks Optimization Based on Genetic Algorithm <https://ieeexplore.ieee.org/document/8011314>`_.
The simalation results for **CS8** can be find in the paper `Detection of SCMA signal with channel estimation error <https://ieeexplore.ieee.org/document/7561515>`_ (defined as **CS2** in the paper).
