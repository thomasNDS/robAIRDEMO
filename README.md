robAIRDEMO
==========
Robair ROS stack with interface
################


Get sources
===========

::

    roscd
    git clone https://github.com/thomasNDS/rrobAIRDEMO.git

Install dependencies
====================


::

    sudo pip install requirement.txt   
    sudo ./setup-debs.sh



Run on Robot
============

Launch ROS:
::
    roscore


In a new terminal:
::

    roscd robAIRDEMO


    make robair


Displays information about ROS topics with rostopic command-line  

::

    rostopic echo /info/battery



Launch Web server
=================

Launch the reservation platform at:
:: https://github.com/thomasNDS/robAirManager.git

Launch the robot link:
:: rosrun robair_node

Launch the serverWeb node
:: rosrun serverWeb


