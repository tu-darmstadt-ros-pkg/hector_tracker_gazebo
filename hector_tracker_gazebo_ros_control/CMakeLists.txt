cmake_minimum_required(VERSION 2.8.3)
project(hector_tracker_gazebo_ros_control)

find_package(catkin REQUIRED COMPONENTS
  gazebo_ros_control
  joint_state_controller
  joint_trajectory_controller
  velocity_controllers
)


catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES hector_tracker_gazebo_ros_control
#  CATKIN_DEPENDS gazebo_ros_control joint_state_controller joint_trajectory_controller velocity_controllers
#  DEPENDS system_lib
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)
