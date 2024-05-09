cmake_minimum_required(VERSION 3.20 FATAL_ERROR)

project(HelloWorld CXX)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED TRUE)

add_executable(hello src/main.cpp)
