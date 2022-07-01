Installation
############

.. note::

  Currently, the package is only available for ROS 2 Rolling, but will be included in ROS 2 I-onwards.

To install the packages, do one of the following:

* `Binary Installation`_
* `Source Installation`_

Binary Installation
*******************

Source your ROS installation, then run:

.. code-block:: console

  sudo apt update
  sudo apt install ros-${ROS_DISTRO}-soccer-vision-3d-rviz-markers

If this method does not work for your platform, perform the `Source Installation`_ instead.

Source Installation
*******************

Source your ROS installation, then run the following in your ROS workspace:

.. code-block:: console

   git clone https://github.com/ros-sports/soccer_vision_3d_rviz_markers.git src/soccer_vision_3d_rviz_markers --branch ${ROS_DISTRO}
   rosdep install --from-paths src -i
   colcon build
