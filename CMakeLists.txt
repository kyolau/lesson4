cmake_minimum_required(VERSION 3.16.3)

project(MAINEXE)

set(CMAKE_BUILD_TYPE "Debug")

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g -O2 -Wall")

add_executable(MAIN_EXE main.cpp)