cmake_minimum_required(VERSION 3.0.0)
project(HelloWorld)

include_directories(include)
add_subdirectory(src ${PROJECT_SOURCE_DIR}/build/bin)

