cmake_minimum_required(VERSION 2.8.3)
project(gazebo_simulation)

add_compile_options(-std=c++11)

find_package(catkin REQUIRED COMPONENTS
  roscpp
  std_msgs
  timed_roslaunch
  robot_bridge
)

catkin_package(
  #INCLUDE_DIRS include
)


include_directories(
  #include
  ${catkin_INCLUDE_DIRS}
)

