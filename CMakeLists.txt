cmake_minimum_required(VERSION 3.21)
project(lab4opmp)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fopenmp -std=c++14")

add_executable(lab4opmp main.cpp)
