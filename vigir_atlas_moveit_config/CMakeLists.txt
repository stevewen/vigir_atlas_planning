cmake_minimum_required(VERSION 2.8.3)
project(vigir_atlas_moveit_config)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY launch DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
install(DIRECTORY config DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
install(FILES rosparam_append DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
