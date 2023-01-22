cmake_minimum_required(VERSION 3.0)
project(cmaketut)

set(CMAKE_BUILD_TYPE    Debug)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++17")

#main app
add_executable(
    hello
    src/main.cpp
    src/add.cpp
)