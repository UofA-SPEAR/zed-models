cmake_minimum_required(VERSION 3.5)

project(zed_models)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY
  urdf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
