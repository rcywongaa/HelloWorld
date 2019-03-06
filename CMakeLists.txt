cmake_minimum_required(VERSION 3.0.0)
set(CMAKE_BUILD_TYPE Debug)
project(HelloWorld)

include_directories(include)
#add_subdirectory(src)

#find_package (Threads REQUIRED)

add_executable(helloworld src/main.cpp)
