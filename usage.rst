Usage
#####

To use the node, simply run:

.. code-block:: sh

  ros2 run soccer_vision_3d_rviz_markers visualizer

This will run the node with default parameters.

Open RViz2 using a configuration file provided by the package:

.. code-block:: sh

  rviz2 -d $(ros2 pkg prefix --share soccer_vision_3d_rviz_markers)/rviz/demo.rviz
