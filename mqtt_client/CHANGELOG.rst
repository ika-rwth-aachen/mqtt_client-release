^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package mqtt_client
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

2.0.1 (2023-06-10)
------------------
* fix unrecognized build type with catkin_make_isolated
  order of statements is somehow revelant; catkin_make_isolated would not detect the build type; build farm jobs were failing; https://build.ros.org/job/Ndev__mqtt_client__ubuntu_focal_amd64/10/console
* Contributors: Lennart Reiher

2.0.0 (2023-06-10)
------------------
* Merge pull request #23 from ika-rwth-aachen/docker-ros
  Integrate docker-ros
* Merge pull request #16 from ika-rwth-aachen/dev/ros2
  Add support for ROS2
* Contributors: Lennart Reiher

1.1.0 (2022-10-13)
------------------
* Merge pull request #6 from ika-rwth-aachen/feature/primitive-msgs
  Support exchange of primitive messages with other MQTT clients
* Contributors: Lennart Reiher

1.0.2 (2022-10-07)
------------------
* Merge pull request #4 from ika-rwth-aachen/improvement/runtime-optimization
  Optimize runtime
* Merge pull request #5 from ika-rwth-aachen/ci
  Set up CI
* Contributors: Lennart Reiher

1.0.1 (2022-08-11)
------------------
* Merge pull request #3 from ika-rwth-aachen/doc/code-api
  Improve Code API Documentation
* Merge pull request #1 from ika-rwth-aachen/improvement/documentation
  Improve documentation
* Contributors: Lennart Reiher
