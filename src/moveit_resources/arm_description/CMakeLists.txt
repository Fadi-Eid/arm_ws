cmake_minimum_required(VERSION 3.10.2)
project(moveit_resources_arm_description)
find_package(ament_cmake REQUIRED)

ament_package()

install(DIRECTORY urdf DESTINATION share/${PROJECT_NAME})
