cmake_minimum_required(VERSION 3.5)
project(regex)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++14")

set(SOURCE_FILES Regex.cpp)
add_executable(regex ${SOURCE_FILES})