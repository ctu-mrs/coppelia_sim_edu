# coppelia_sim_edu

A deb package source for automating the download of Coppelia Sim EDU.

The `ros2` branch installs CoppeliaSim EDU V4.10.0 (rev0) for Ubuntu 24.04 (ROS 2 Jazzy) into `/opt/coppelia-sim-edu`.

The bundled simROS2 plugin does not support the `mrs_msgs` interfaces, so the package rebuilds it after installation and whenever `mrs_msgs` gets updated.

To rebuild it manually, run `sudo coppelia-sim-build-ros2-plugin`.
