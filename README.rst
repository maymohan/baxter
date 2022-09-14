Baxter SDK ROS Noetic fork
===========================

This is a ROS Noetic/Python3 compatible fork of the Baxter SDK. Please follow the installation instructions described in the `wiki of this repository <https://github.com/maymohan/baxter/wiki/Installation-Instructions>`__. These instructions will install the SDK components i.e. baxter_interface, baxter_tools, baxter_common and baxter_examples. However, it will not install baxter_simulator and baxter_pykdl. Please navigate to those repositories separately via the links provided below and follow the instructions provided within the respective repositories.

ROS Noetic compatible Baxter repositories that the rosinstall file includes can be found here:


+------------------+-----------------------------------------------------+
| baxter_interface | https://github.com/maymohan/baxter_interface        |
+------------------+-----------------------------------------------------+
| baxter_tools     | https://github.com/maymohan/baxter_tools            |
+------------------+-----------------------------------------------------+
| baxter_common    | https://github.com/maymohan/baxter_common           |
+------------------+-----------------------------------------------------+
| baxter_examples  | https://github.com/maymohan/baxter_examples         |
+------------------+-----------------------------------------------------+

Other Baxter Repositories (must be installed separately):

+------------------+-----------------------------------------------------+
| baxter_pykdl     | https://github.com/maymohan/baxter_pykdl            |
+------------------+-----------------------------------------------------+
| baxter_simulator | https://github.com/maymohan/baxter_simulator        |
+------------------+-----------------------------------------------------+

Test Installation:
------------------
Test your installation by following the instructions in the link provided below: https://sdk.rethinkrobotics.com/wiki/Hello_Baxter

Baxter Repository Overview
--------------------------

::

     .
     |
     +-- baxter_sdk/              baxter metapackage containing all baxter sdk packages
     |
     +-- baxter_sdk.rosinstall    rosinstall script containing all baxter sdk packages
     |
     +-- baxter.sh                convenient environment initialization script
     

References: Code & Tickets (for original repository)
----------------------------------------------------

+-----------------+----------------------------------------------------------------+
| Documentation   | http://sdk.rethinkrobotics.com/wiki                            |
+-----------------+----------------------------------------------------------------+
| Issues          | https://github.com/RethinkRobotics/baxter/issues               |
+-----------------+----------------------------------------------------------------+
| Contributions   | http://sdk.rethinkrobotics.com/wiki/Contributions              |
+-----------------+----------------------------------------------------------------+


References: Original Baxter Repositories
-----------------------------------------
+------------------+-----------------------------------------------------+
| baxter_interface | https://github.com/RethinkRobotics/baxter_interface |
+------------------+-----------------------------------------------------+
| baxter_tools     | https://github.com/RethinkRobotics/baxter_tools     |
+------------------+-----------------------------------------------------+
| baxter_common    | https://github.com/RethinkRobotics/baxter_common    |
+------------------+-----------------------------------------------------+
| baxter_examples  | https://github.com/RethinkRobotics/baxter_examples  |
+------------------+-----------------------------------------------------+
| baxter_pykdl     | https://github.com/RethinkRobotics/baxter_pykdl     |
+------------------+-----------------------------------------------------+
| baxter_simulator | https://github.com/RethinkRobotics/baxter_simulator |
+------------------+-----------------------------------------------------+
