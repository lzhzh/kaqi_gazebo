cmake_minimum_required(VERSION 2.8.3)
project(kaqi_gazebo)

## Find catkin macros and libraries
## if COMPONENTS list like find_package(catkin REQUIRED COMPONENTS xyz)
## is used, also find other catkin packages
find_package(catkin REQUIRED COMPONENTS
  kaqi_description
  xacro
)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES kaqi_gazebo
#  CATKIN_DEPENDS kaqi_description xacro
#  DEPENDS system_lib
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)

