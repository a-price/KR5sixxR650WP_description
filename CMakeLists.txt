cmake_minimum_required(VERSION 2.8.3)
project(KR5sixxR650WP_description)

## Find catkin macros and libraries
find_package(catkin REQUIRED)

###################################
## catkin specific configuration ##
###################################

catkin_package()

#############
## Install ##
#############

install(DIRECTORY launch DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
install(DIRECTORY robots DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
install(DIRECTORY meshes DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
