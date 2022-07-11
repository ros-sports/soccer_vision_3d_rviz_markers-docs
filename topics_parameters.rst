Topics / Parameters
###################

List of topics used by the node.

Subscribed Topics
*****************

* **/soccer_vision_3d/balls** (`soccer_vision_3d_msgs/msg/BallArray`_)
* **/soccer_vision_3d/field_boundary** (`soccer_vision_3d_msgs/msg/FieldBoundary`_)
* **/soccer_vision_3d/goalposts** (`soccer_vision_3d_msgs/msg/GoalpostArray`_)
* **/soccer_vision_3d/markings** (`soccer_vision_3d_msgs/msg/MarkingArray`_)
* **/soccer_vision_3d/obstacles** (`soccer_vision_3d_msgs/msg/ObstacleArray`_)
* **/soccer_vision_3d/robots** (`soccer_vision_3d_msgs/msg/RobotArray`_)

Published Topics
****************

* **/visualization/balls** (`visualization_msgs/msg/MarkerArray`_)
* **/visualization/field_boundary** (`visualization_msgs/msg/Marker`_)
* **/visualization/goalposts** (`visualization_msgs/msg/MarkerArray`_)
* **/visualization/markings** (`visualization_msgs/msg/MarkerArray`_)
* **/visualization/obstacles** (`visualization_msgs/msg/MarkerArray`_)
* **/visualization/robots** (`visualization_msgs/msg/MarkerArray`_)

Parameters
**********

.. _ball_diameter:

* **ball_diameter** (*float*, default="0.10")

  Diameter of the ball in meters.

.. _marking_segment_width:

* **marking_segment_width** (*float*, default="0.05")

  Width of a marking segment in meters.

.. _field_boundary_line_width:

* **field_boundary_line_width** (*float*, default="0.02")

  Width of the field boundary line in meters.


.. _soccer_vision_3d_msgs/msg/BallArray: https://github.com/ros-sports/soccer_interfaces/blob/rolling/soccer_vision_3d_msgs/msg/BallArray.msg
.. _soccer_vision_3d_msgs/msg/FieldBoundary: https://github.com/ros-sports/soccer_interfaces/blob/rolling/soccer_vision_3d_msgs/msg/FieldBoundary.msg
.. _soccer_vision_3d_msgs/msg/GoalpostArray: https://github.com/ros-sports/soccer_interfaces/blob/rolling/soccer_vision_3d_msgs/msg/GoalpostArray.msg
.. _soccer_vision_3d_msgs/msg/MarkingArray: https://github.com/ros-sports/soccer_interfaces/blob/rolling/soccer_vision_3d_msgs/msg/MarkingArray.msg
.. _soccer_vision_3d_msgs/msg/ObstacleArray: https://github.com/ros-sports/soccer_interfaces/blob/rolling/soccer_vision_3d_msgs/msg/ObstacleArray.msg
.. _soccer_vision_3d_msgs/msg/RobotArray: https://github.com/ros-sports/soccer_interfaces/blob/rolling/soccer_vision_3d_msgs/msg/RobotArray.msg

.. _visualization_msgs/msg/Marker: https://github.com/ros2/common_interfaces/blob/rolling/visualization_msgs/msg/Marker.msg
.. _visualization_msgs/msg/MarkerArray: https://github.com/ros2/common_interfaces/blob/rolling/visualization_msgs/msg/MarkerArray.msg
