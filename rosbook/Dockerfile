from ros
run apt-get update
#run ["/bin/bash","-c","source /opt/ros/kinetic/setup.bash"]
#run source /opt/ros/kinetic/setup.bash
run apt-get install -y ros-kinetic-moveit-core
run apt-get install -y ros-kinetic-gazebo-ros
run apt-get install -y ros-kinetic-pcl-ros
run apt-get install -y ros-kinetic-angles
run apt-get install -y ros-kinetic-image-geometry ros-kinetic-diagnostics ros-kinetic-control-toolbox
run apt-get install -y software-properties-common python-software-properties
run add-apt-repository --yes ppa:xqms/opencv-nonfree
run apt-get update
run apt-get install -y libopencv-nonfree-dev libopencv-nonfree2.4v5
run apt-get install -y ros-kinetic-image-transport ros-kinetic-cv-bridge
run apt-get install -y  ros-kinetic-moveit-visual-tools
run apt-get install -y  ros-kinetic-gazebo-ros-control
run apt-get install -y ros-kinetic-camera-info-manager
run apt-get install -y ros-kinetic-dynamixel-motor
run apt-get install -y ros-kinetic-joy ros-kinetic-joystick-drivers
run apt-get install -y ros-kinetic-fake-localization
run apt-get install -y ros-kinetic-laser-filters
run apt-get install -y ros-kinetic-map-server
run apt-get install -y ros-kinetic-robot-state-publisher
run apt-get install -y ros-kinetic-moveit-ros-planning-interface ros-kinetic-xacro
run apt-get install -y ros-kinetic-move-base-msgs
#run apt-get install -y ros-kinetic-moveit-simple-grasps
run mkdir /ros_book_ws 
run mkdir /ros_book_ws/src
#run cd /ros_book_ws/src && catkin_init_workspace
run ["/bin/bash","-c","source /opt/ros/kinetic/setup.bash;cd /ros_book_ws/src && catkin_init_workspace"]
add  moveit_simple_grasps /ros_book_ws/src/moveit_simple_grasps
#add  effective_robotics_programming_with_ros /ros_book_ws/src/effective_robotics_programming_with_ros
run ["/bin/bash","-c","source /opt/ros/kinetic/setup.bash;cd /ros_book_ws/ && catkin_make"]
add  effective_robotics_programming_with_ros /ros_book_ws/src/effective_robotics_programming_with_ros
run ["/bin/bash","-c","source /opt/ros/kinetic/setup.bash;cd /ros_book_ws/ && catkin_make"]
