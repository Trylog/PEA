cmake_minimum_required(VERSION 3.24)
project(TSP)

set(CMAKE_CXX_STANDARD 20)
set (CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -static-libstdc++ -static-libgcc")
set(CMAKE_EXE_LINKER_FLAGS "-static")

add_executable(TSP main.cpp GraphMatrix.h GraphMatrix.cpp)
