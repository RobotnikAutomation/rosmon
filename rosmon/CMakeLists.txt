
cmake_minimum_required(VERSION 2.8)
project(rosmon)

find_package(catkin)

catkin_package()

install(
	PROGRAMS src/rosmon
	DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
)
