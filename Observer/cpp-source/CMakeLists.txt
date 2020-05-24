cmake_minimum_required(VERSION 3.5)

project(Observer)

set("CMAKE_CXX_FLAGS" "${CMAKE_CXX_FLAGS} -pthread")

add_executable(Observer main.cpp)
