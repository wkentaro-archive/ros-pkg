========================
rospy_service_experiment
========================

Service call when server is killed
==================================

1. Launch the server and client.
1. Kill the server node when the client is waing for response. (you can see the output of the terminal screen)
1. The client can notice the killed server and re-call the service.

.. code-block:: sh

    roslaunch rospy_service_experiment add_two_ints_respawn.launch
    rosnode kill /add_two_ints_server  # kill the server