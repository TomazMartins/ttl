# Specify the minimum version for CMake
#
cmake_minimum_required( VERSION 2.8 )

# Project's Name
#
project( ttl )

# Set the output folder where your program will be created
#
set( CMAKE_BINARY_DIR ${CMAKE_SOURCE_DIR}/bin )
set( EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR}/bin )
set( LIBRARY_OUTPUT_PATH ${PROJECT_BINARY_DIR}/lib )

# The following folder will be included
#
include_directories( "${PROJECT_SOURCE_DIR}" )
