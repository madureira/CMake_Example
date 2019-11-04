cmake_minimum_required (VERSION 3.10)

# Executable
add_executable(${PROJECT_NAME} ${PROJECT_SOURCE_PATH}/main.cpp)


# Modules
set(MATH_MODULE_PATH ${PROJECT_SOURCE_PATH}/Math)


# Libraries
add_library(Math STATIC ${MATH_MODULE_PATH}/Math.cpp)
target_link_libraries(${PROJECT_NAME} Math)
