cmake_minimum_required(VERSION 3.16)
project(testC++11 CXX)

set(CMAKE_CXX_COMPILER "/opt/gcc11/bin/c++")
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_FLAGS "-Wall -pedantic")

add_executable(test main.cpp)
