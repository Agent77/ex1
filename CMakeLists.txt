cmake_minimum_required(VERSION 3.6)
project(ex1)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp Point.h Point.cpp BFS.h BFS.cpp Node.cpp Node.h Graph.h Graph.cpp Grid.cpp Grid.h Coordinate.h Coordinate.cpp TestPointerArray.cpp TestPointerArray.h)
add_executable(ex1 ${SOURCE_FILES})