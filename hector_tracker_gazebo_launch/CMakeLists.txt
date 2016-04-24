cmake_minimum_required(VERSION 2.8.3)
project(hector_tracker_gazebo_launch)

find_package(catkin REQUIRED COMPONENTS
  gazebo_ros
  hector_tracker_description
  hector_tracker_gazebo_ros_control
)


catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES hector_tracker_gazebo_launch
#  CATKIN_DEPENDS gazebo_ros hector_tracker_description hector_tracker_gazebo_ros_control
#  DEPENDS system_lib
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)
