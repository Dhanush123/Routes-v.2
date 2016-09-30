cmake_minimum_required(VERSION 3.6)
project(Routes_v_2)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES Routes.2.cpp)
add_executable(Routes_v_2 ${SOURCE_FILES})