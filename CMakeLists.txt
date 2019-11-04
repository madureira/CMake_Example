cmake_minimum_required (VERSION 3.10)

set(PROJECT_NAME CMake_Example)

project(${PROJECT_NAME})

set(CMAKE_CXX_STANDARD 11)
set(EXECUTABLE_OUTPUT_PATH ${CMAKE_SOURCE_DIR}/bin)
set(PROJECT_SOURCE_PATH ${CMAKE_SOURCE_DIR}/src)

# Include sub-projects.
add_subdirectory ("src")
