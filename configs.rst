Configs
#######

YAML Configuration files for leagues below are included in the package:

* ``spl.yaml`` - RoboCup Standard Platform League
* ``hl_kid.yaml`` - RoboCup Humanoid League Kid Size
* ``hl_adult.yaml`` - RoboCup Humanoid League Adult Size

You can also write your own config files instead of using ones provided.

ROS 2 CLI
*********

When using ros2cli (``ros2 run``) to run your node, load the config (replace ``hl_adult.yaml`` with your desired config) as below:

.. code-block:: sh

  ros2 run soccer_vision_3d_rviz_markers visualizer --ros-args --params-file $(ros2 pkg prefix --share soccer_vision_3d_rviz_markers)/config/hl_adult.yaml

Launch File
***********

When running the node from a launch file, load the config (replace ``hl_adult.yaml`` with your desired config) and pass it to the node constructor as below:

.. code-block:: py

  import os
  from ament_index_python.packages import get_package_share_directory
  from launch import LaunchDescription
  from launch_ros.actions import Node
  def generate_launch_description():
      ld = LaunchDescription()
      config = os.path.join(
          get_package_share_directory('soccer_vision_3d_rviz_markers'),
          'config',
          'hl_adult.yaml'
          )

      node = Node(
          package='soccer_vision_3d_rviz_markers',
          executable='visualizer',
          parameters=[config]
          )
      ld.add_action(node)
      return ld

