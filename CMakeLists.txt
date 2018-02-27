cmake_minimum_required(VERSION 3.8)
project(FSM)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp road.cpp road.h vehicle.cpp vehicle.h cost.cpp cost.h)
add_executable(FSM ${SOURCE_FILES})