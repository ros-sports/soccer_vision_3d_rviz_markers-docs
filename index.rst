.. Soccer Vision 3D RViz Markers documentation master file, created by
   sphinx-quickstart on Fri Jul  1 13:55:37 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Soccer Vision 3D RViz Markers
=============================

Soccer Vision 3D RViz Markers is a ROS 2 package that converts `Soccer Vision 3D Msgs`_ to RViz Markers to help visualize the data.

The visualizer node simply listens for ball, field boundary, goalposts, markings, obstacles and robots, converts them to visualization markers and publishes them so they can be visualized in RViz.

The project is hosted on `Github`_ by ROS Sports.

.. toctree::
   :hidden:
   :maxdepth: 2

   installation
   usage
   visualization
   topics_parameters
   configs

.. _Soccer Vision 3D Msgs: https://index.ros.org/p/soccer_vision_3d_msgs/
.. _Github: https://github.com/ros-sports/soccer_vision_3d_rviz_markers
