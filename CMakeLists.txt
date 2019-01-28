cmake_minimum_required(VERSION 3.0.0)
set(CMAKE_BUILD_TYPE Debug)
project(HelloWorld)

include_directories(include)
add_subdirectory(lib/HelloLib)
add_subdirectory(src ${PROJECT_SOURCE_DIR}/build/bin)

